# 🌐 How to Host a Static Site Using GitHub Pages

GitHub Pages offers a free and reliable way to host static websites directly from a GitHub repository. Whether you're showcasing a portfolio, documentation, or a blog, it’s a great tool for developers and creators alike.

This guide walks you through setting up and deploying a static site using GitHub Pages.

---

## 📁 1. Prepare Your Static Site Files

Make sure your static website is ready to be published. This includes:
- An `index.html` file as the homepage
- Optional folders like `/css`, `/js`, or `/images`
- A `README.md` file (recommended)

You can generate static sites manually or using static site generators like Jekyll, Hugo, or Eleventy.

---

## 🧑‍💻 2. Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in.
2. Click **New Repository**.
3. Name your repo (e.g., `my-static-site`).
4. Choose **Public** or **Private**.
5. Click **Create Repository**.

You can initialize it with a `README.md` or push code later.

---

## ⬆️ 3. Upload or Push Your Code

If you're using the GitHub website:
- Click **Add file → Upload files** to upload your project.

If you're using Git:
```bash
git clone https://github.com/your-username/my-static-site.git
cd my-static-site
# Add your files
# Then push them:
git add .
git commit -m "Initial commit"
git push origin main
```

---

## 🚀 4. Enable GitHub Pages

1. Go to your repo’s **Settings** tab.
2. Scroll to **Pages**.
3. Under **Source**, select `main` branch and `/ (root)` folder.
4. Click **Save**.

GitHub will provide a URL like:
```
https://your-username.github.io/my-static-site/
```
It may take a few minutes to appear.

---

## 🧪 5. Test and Update

Visit your GitHub Pages URL to view your live site. Make updates by pushing changes to the repository:
```bash
git add .
git commit -m "Update content"
git push origin main
```
GitHub automatically rebuilds the site on every push.

---

## 🔐 Bonus: Custom Domain (Optional)

You can use your own domain:
1. Create a `CNAME` file in your repo with your domain name.
2. Configure DNS settings with your domain provider (point to GitHub Pages IPs).

---

## ✅ Summary

| Step                        | Description                                      |
|-----------------------------|--------------------------------------------------|
| 1. Prepare site             | HTML/CSS/JS files in a folder                    |
| 2. Create GitHub repo       | Public or private                                |
| 3. Upload or push code      | Git or web upload                                |
| 4. Enable GitHub Pages      | Set source branch and folder                     |
| 5. Publish + test           | Access your live site on the provided URL        |

GitHub Pages is perfect for simple, fast, and cost-free web publishing.

---

📝 Written by B [NeutralStack](https://github.com/neutralstack) — exploring platforms, creators, and community-driven design.
