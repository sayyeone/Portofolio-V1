# Portfolio - V1

A modern dark-themed portfolio website with clean typography and smooth animations. Built to showcase my journey as a Computer Science student.

**Live Demo:** [Portofolio-V1](https://sayyeone.github.io/Portofolio-V1/)

## What's This?

My personal portfolio website featuring a modern dark design with purple gradient accents. Includes sections for about me, projects, and contact information. Perfect for showcasing my skills and connecting with potential collaborators.

## Tech Stack

Just the essentials:
* HTML5
* Tailwind CSS (via CDN)
* Google Fonts (Inter)
* Vanilla JavaScript for smooth scrolling

No build tools needed. Clone and open.

## Getting Started

**Option 1: Just open it**

Clone the repo and double-click `index.html`. Done.
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
# Double click index.html
```

**Option 2: Use Live Server (recommended)**

If you're using VS Code:
1. Install the Live Server extension
2. Right click `index.html` → Open with Live Server
3. Browser opens automatically at `localhost:5500`

**Option 3: Python server**
```bash
python -m http.server 8000
# Open http://localhost:8000 in your browser
```

## Deploying to GitHub Pages

Want to put this online? Super easy.

1. Push your code to GitHub:
```bash
git add .
git commit -m "initial commit"
git push origin main
```

2. Go to your repo → Settings → Pages
3. Under "Source", select `main` branch and `/ (root)` folder
4. Hit Save and wait a minute

Your site will be live at `https://yourusername.github.io/portfolio`

**Custom Domain**

Got your own domain? Create a `CNAME` file with your domain:
```
yourdomain.com
```

Then configure DNS with your domain provider. Wait 24 hours for propagation.

## Customizing

Everything's straightforward to customize.

**Change colors:** Edit the gradient in the `<style>` section:
```css
.gradient-text {
    background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
}
```

**Update profile photo:** Replace the image URLs:
```html
<img src="your-photo.jpg" alt="Profile">
```

**Modify skills:** Edit the skill tags in the About section:
```html
<span class="bg-gray-700 text-purple-400 px-6 py-3 rounded-full">Your Skill</span>
```

**Change social links:** Update URLs in the Contact section:
```html
<a href="https://github.com/yourusername" target="_blank">
```

## Project Structure
```
portfolio/
├── index.html          # Main portfolio page
├── README.md           # You're reading it
└── img/                # Image assets (optional)
```

Super simple structure - easy to understand and modify.

## Features

* **Hero Section** - Eye-catching intro with gradient text and profile photo
* **About Section** - Background info and skill tags
* **Projects Section** - Direct link to GitHub repositories
* **Contact Form** - Clean UI for getting in touch (UI only, JS coming soon)
* **Social Links** - GitHub, LinkedIn, and Email with icons
* **Smooth Scrolling** - Navigation jumps smoothly between sections
* **Responsive Design** - Looks great on all devices
* **Dark Theme** - Easy on the eyes with purple accents
* **Modern Typography** - Inter font for clean, professional look

## Browser Support

Works on all modern browsers:
* Chrome (latest)
* Firefox (latest)
* Safari (latest)
* Edge (latest)

## Credits

* Tailwind CSS for styling
* Google Fonts for Inter typeface
* Placeholder images from placeholder.com

---

Made with ❤️ by [Sayyeone](https://github.com/sayyeone)

Questions? Open an issue or reach out!
