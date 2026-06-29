# 🚀 GitHub Profile Setup Guide

## ✅ Already Completed
- ✅ World-class README.md created
- ✅ GitHub Actions workflows added
- ✅ All files pushed to repository

---

## 📝 Step-by-Step Setup Instructions

### 1️⃣ Enable GitHub Actions

1. Go to: https://github.com/khanzadigithubid/khanzadigithubid
2. Click on **Settings** tab
3. In left sidebar: **Actions** > **General**
4. Select: **"Allow all actions and reusable workflows"**
5. Scroll down to **Workflow permissions**
6. Select: **"Read and write permissions"**
7. Check: **"Allow GitHub Actions to create and approve pull requests"**
8. Click **Save**

---

### 2️⃣ Run Snake Animation (First Time)

1. Go to: https://github.com/khanzadigithubid/khanzadigithubid/actions
2. Click on **"Generate Snake Animation"** workflow (left sidebar)
3. Click **"Run workflow"** button (right side)
4. Select **"master"** branch
5. Click green **"Run workflow"** button
6. Wait 1-2 minutes for completion

The snake will now update automatically every 12 hours!

---

### 3️⃣ WakaTime Setup (Optional - For Coding Stats)

#### A. Create WakaTime Account
1. Visit: https://wakatime.com/signup
2. Sign up with GitHub
3. Verify your email

#### B. Get API Key
1. Go to: https://wakatime.com/settings/account
2. Copy your **Secret API Key**

#### C. Install WakaTime Extension
**For VS Code:**
1. Open VS Code
2. Press `Ctrl+Shift+X` (Extensions)
3. Search: "WakaTime"
4. Click **Install**
5. Paste your API key when prompted

**For Other Editors:**
- Visit: https://wakatime.com/plugins

#### D. Add Secret to GitHub
1. Go to: https://github.com/khanzadigithubid/khanzadigithubid/settings/secrets/actions
2. Click **"New repository secret"**
3. Name: `WAKATIME_API_KEY`
4. Value: Paste your WakaTime API key
5. Click **Add secret**

#### E. Trigger Workflow
1. Go to: https://github.com/khanzadigithubid/khanzadigithubid/actions
2. Click **"WakaTime Stats"**
3. Click **"Run workflow"**
4. Wait for completion

---

### 4️⃣ Blog Posts Setup (Optional)

#### Option A: Dev.to
1. Create account: https://dev.to/
2. Your username will be: `khanzadi` (or whatever you choose)
3. Update README.md line with blog workflow:
   ```yaml
   feed_list: "https://dev.to/feed/YOUR_USERNAME"
   ```

#### Option B: Medium
1. Create account: https://medium.com/
2. Update workflow file to use Medium RSS feed

#### Option C: Disable Blog Section
If you don't want blog posts, you can:
1. Delete `.github/workflows/blog-posts.yml`
2. Remove the blog section from README.md

---

### 5️⃣ Customize Your Profile

Edit `README.md` to personalize:

- **Line 7**: Change typing animation text
- **Line 34-50**: Update your information in the code block
- **Line 55**: Update your current projects
- **Line 298-305**: Update featured projects (replace with your actual repos)
- **Line 373**: Add your LinkedIn URL
- **Line 623**: Update Spotify username (or remove section)
- **Line 641**: Add portfolio URL

---

### 6️⃣ Fix Profile Picture & Social Links

#### Profile Picture
The animated GIF at line 5 needs to be:
1. Upload an image to your repo
2. Or use a direct URL
3. Replace: `src="6f872e3ca7ad565c0a2904a47f08f6e5.jpg"`

#### Social Links
Update these sections with your actual URLs:
- LinkedIn (line 373)
- Twitter (line 383)
- Dev.to (line 388)
- Portfolio (line 378)

---

## 🎯 Testing Your Setup

### Check if Everything Works

1. **Snake Animation**
   - Visit: https://github.com/khanzadigithubid/khanzadigithubid
   - Scroll to snake section
   - Should see animated snake after first workflow run

2. **GitHub Stats**
   - All stat cards should load automatically
   - No setup needed!

3. **Profile Views Counter**
   - Will increment each time someone visits
   - Works immediately

4. **WakaTime Stats**
   - Start coding with WakaTime extension
   - Stats appear after 24 hours
   - Updates daily

---

## 🔧 Troubleshooting

### Snake Animation Not Showing?
- Check if workflow ran successfully in Actions tab
- Make sure workflow permissions are set to "Read and write"
- Wait 5-10 minutes after first run

### WakaTime Not Updating?
- Verify API key is correct
- Make sure secret name is exactly: `WAKATIME_API_KEY`
- Code for at least 1 hour to see stats

### Stats Cards Not Loading?
- These work automatically via Vercel
- If not loading, check your internet connection
- Try different browser

---

## 📞 Need Help?

- **GitHub Actions Issues**: Check Actions tab for error messages
- **WakaTime Issues**: https://wakatime.com/help
- **General Questions**: Open an issue in your repo

---

## 🎉 You're All Set!

Your GitHub profile is now:
- ✅ Professional & eye-catching
- ✅ Auto-updating with stats
- ✅ Showing live coding activity
- ✅ Ready to impress recruiters!

**Profile URL**: https://github.com/khanzadigithubid

---

*Last Updated: June 2024*
*Made with ❤️ using Claude Code*
