# Blog Directory

This directory contains all your blog posts.

## How to Add a New Blog Post

### Step 1: Create a New Blog Post File

1. Copy the `template.html` file and rename it to your post title (use hyphens for spaces)
   - Example: `my-first-post.html` or `learning-javascript.html`

2. Open your new file and edit:
   - **Title**: Change `<title>Post Title - Younes Hatti</title>` to your post title
   - **Meta Description**: Update the meta description
   - **Date**: Update the `<time datetime="2026-01-22">` to your post date
   - **H1 Heading**: Change "Post Title Here" to your actual title
   - **Content**: Write your blog post in the `.post-content` div

### Step 2: Add the Post to Your Homepage

1. Open `../index.html`
2. Find the blog section (around line 60-70)
3. Add your post inside the `<div class="blog-list">` section:

```html
<article class="blog-post">
    <h3><a href="blog/my-first-post.html">My First Post</a></h3>
    <time datetime="2026-01-22">January 22, 2026</time>
    <p>A brief description of your blog post (1-2 sentences).</p>
</article>
```

### Step 3: Update Google Analytics (Optional)

If you have a Google Analytics ID:
1. Replace `YOUR_GA_ID` in both `index.html` and your blog post files
2. Or remove the Google Analytics script entirely if you don't use it

## Styling Tips

- Use `<h2>` for main sections (automatically styled in royal green)
- Use `<h3>` for subsections
- Use `<blockquote>` for important quotes or notes
- Add images: `<img src="../assets/images/your-image.jpg" alt="Description" style="width: 100%; border-radius: 12px; margin: 1rem 0;">`
- Add links: `<a href="https://example.com" style="color: var(--royal-green-light);">Link text</a>`

## File Organization

```
blog/
├── README.md          (this file)
├── template.html      (copy this to create new posts)
├── my-first-post.html (your blog posts)
└── another-post.html  (your blog posts)
```

## Quick Reference

- Royal Green color: `var(--royal-green)`
- Gold Accent: `var(--gold-accent)`
- Text color: `var(--text-primary)` or `var(--text-secondary)`

That's it! Your website is designed to be simple and easy to maintain.
