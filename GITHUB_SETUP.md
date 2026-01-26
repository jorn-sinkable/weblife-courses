# GitHub Setup - Quick Instructions

## Step 1: Create GitHub Repository

1. Go to **https://github.com/new**
2. Repository name: `weblife-courses`
3. Description: `WebLife Onboarding Course Catalog`
4. Make it **Public**
5. Do NOT initialize with README
6. Click **Create repository**

## Step 2: Push Your Code

You will see a page with commands. Run these in your terminal:

```bash
cd /sessions/optimistic-wonderful-ramanujan/weblife-courses
git remote add origin https://github.com/jornwossner/weblife-courses.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. In your repository, go to **Settings**
2. Click **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes

## Step 4: Get Your Live URL

Your course catalog will be live at:

**https://jornwossner.github.io/weblife-courses/course-catalog.html**

## Step 5: Embed in ClickUp

1. Open ClickUp Doc
2. Type `/embed`
3. Paste: `https://jornwossner.github.io/weblife-courses/course-catalog.html`
4. Set height to 1000px
5. Done!

---

## Already Set Up?

If you already created the repository, just run:

```bash
cd /sessions/optimistic-wonderful-ramanujan/weblife-courses
git push -u origin main
```

Then enable GitHub Pages in Settings → Pages.
