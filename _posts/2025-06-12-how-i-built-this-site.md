---
layout: post
title: "How I Built This Brain Dump Site (and How You Can Too)"
#date: 2025-06-12
categories: [how-to, dev]
tags: [github-pages, jekyll, moonrise, personal-site]
---

So you want to create your own **brain dump site** to store notes, share projects, or just document your learning journey?

In this post, I’ll walk you through how I built [mell0wx.github.io](https://mell0wx.github.io) using GitHub Pages and the **Moonrise Jekyll theme**, and how *you* can create a similar personal site — completely free.

---

## 🛠️ Tools I Used

- **GitHub** (for hosting the code)
- **GitHub Pages** (for publishing the site)
- **Jekyll** (a static site generator)
- **Moonrise** ([link to theme](https://github.com/TolgaTatli/Moonrise)) for the dark, clean design
- **Markdown** for writing content

---

## 🔧 Step-by-Step: How I Did It

### 1. **Create a GitHub Repository**

Name your repository following this format:

"yourusername.github.io"


GitHub will automatically recognize this as a personal website.

---

### 2. **Choose a Jekyll Theme**

I used [Moonrise](https://github.com/TolgaTatli/Moonrise) for its elegant dark aesthetic. To use it:

- Clone the theme repo or download the ZIP  
- Replace the contents of your repo with the theme files

```bash
git clone https://github.com/TolgaTatli/Moonrise.git
cd Moonrise
```

Then push it to your GitHub Pages repo:
```bash
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### 3. Customize _config.yml

Update this file to personalize the site:

title: "My Brain Dump"
description: "A collection of everything I'm learning and doing"
author: your_name
baseurl: ""
url: "https://yourusername.github.io"

You can also enable collections like posts, notes, or projects.

### 4. Write Your First Posts

Create Markdown files in _posts/ following the Jekyll format:
YYYY-MM-DD-title-of-post.md

Example:
---
layout: post
title: "Welcome to My Brain Dump"
date: 2025-06-12
categories: [intro]
---
Your content goes here...

### 5. Enable GitHub Pages

Go to your repo → Settings → Pages → Choose the main branch and root folder.

GitHub will build the site and host it at:
https://yourusername.github.io

### ✍️ Tips for Content Creation

    Use Markdown for fast, readable writing

    Organize posts by topic using categories or tags

    Use folders like _projects/ or _notes/ to separate content

    Add screenshots, diagrams, or code snippets for clarity

### 💡 Why This Setup Works

    💸 Free hosting with GitHub Pages

    📚 Simple format with Jekyll + Markdown

    🎨 Customizable theme like Moonrise

    ✍️ Easy to maintain and expand over time

You don’t need to be a web developer to do this — if you can write Markdown and push to GitHub, you can create a professional-looking knowledge site.

### ✅ Final Thoughts

This site is my sandbox. I use it to:

    Document learning

    Store walkthroughs & lab builds

    Share scripts and research

    Reflect on tech, finance, and hobbies

If you want to create your own, just fork a theme you like, push it to GitHub Pages, and start writing. The rest will come naturally.

Have questions or want to share your own setup? Reach out — I'd love to see what you build.

Happy documenting 🧠




