# Tony Legend's Portfolio

A modern, responsive portfolio site built with Hugo and deployed on Vercel.

## 🚀 Features

- **Modern Design** - Clean, professional layout
- **Projects Showcase** - Display your work with detailed project pages
- **Blog Section** - Share your thoughts and insights
- **About & Contact** - Tell your story and make it easy to get in touch
- **SEO Optimized** - Built-in SEO best practices
- **Mobile Responsive** - Looks great on all devices
- **Fast & Lightweight** - Static site generation for optimal performance

## 📋 Prerequisites

- [Hugo](https://gohugo.io/) installed on your machine
- [Git](https://git-scm.com/)
- GitHub account
- Vercel account

## 🛠️ Installation & Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/TonyLegend-77/portfolio.git
   cd portfolio
   ```

2. **Install Hugo Theme**
   ```bash
   git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
   ```

3. **Run local development server**
   ```bash
   hugo server -D
   ```

4. **Visit your site**
   Open `http://localhost:1313` in your browser

## 📝 Customization

### Update Site Information

Edit `config.toml` to customize:
- Site title and description
- Author name
- Base URL

### Add New Projects

1. Create a new markdown file in `content/projects/`
2. Add your project details with front matter (title, date, tags, etc.)
3. Save and your project will appear on the Projects page

### Add Blog Posts

1. Create a new markdown file in `content/blog/`
2. Add post metadata in the front matter
3. Write your content in markdown

### Edit Pages

- Home: `content/_index.md`
- About: `content/about.md`
- Contact: `content/contact.md`
- Projects: `content/projects/_index.md`
- Blog: `content/blog/_index.md`

## 🚀 Deployment on Vercel

1. **Push to GitHub**
   ```bash
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Select your GitHub repository
   - Vercel will auto-detect Hugo settings
   - Click Deploy

3. **Your site is live!**
   Vercel will provide a URL and automatic deployments on every push

## 📚 Project Structure

```
portfolio/
├── content/
│   ├── _index.md           # Home page
│   ├── about.md            # About page
│   ├── contact.md          # Contact page
│   ├── blog/               # Blog posts
│   │   ├── _index.md
│   │   └── first-post.md
│   └── projects/           # Project showcases
│       ├── _index.md
│       ├── project-1.md
│       └── project-2.md
├── themes/                 # Hugo themes
│   └── ananke/
├── static/                 # Static files (images, CSS, JS)
├── config.toml            # Site configuration
├── vercel.json            # Vercel configuration
├── package.json           # Project metadata
└── README.md             # This file
```

## 🎨 Customizing the Theme

The portfolio uses the [Ananke](https://themes.gohugo.io/themes/gohugo-theme-ananke/) theme. To customize:

1. Copy theme files to `layouts/` directory
2. Modify as needed
3. Changes override theme defaults

## 📞 Support

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Vercel Docs](https://vercel.com/docs)
- [Ananke Theme Docs](https://github.com/theNewDynamic/gohugo-theme-ananke)

## 📄 License

This project is open source and available under the MIT License.

---

**Ready to showcase your work?** Update the content files with your information and deploy! 🎉
