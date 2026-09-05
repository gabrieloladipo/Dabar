# 🎨 Dabar Designs - Graphic Design Portfolio

A modern, fully responsive portfolio website showcasing graphic design work, skills, and services.

## ✨ Features

- **Modern Dark Theme** - Sleek dark design with blue and purple gradient accents
- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations** - Interactive scroll effects and hover animations
- **Animated Progress Bars** - Skill proficiency indicators with smooth animations
- **Mobile-Friendly Navigation** - Hamburger menu for mobile devices
- **Contact Form** - Integrated with Formspree for direct email submissions
- **Project Gallery** - Showcase 6 different design projects
- **SEO Optimized** - Meta tags for better search engine visibility

## 📋 Sections

1. **Home/Hero** - Eye-catching introduction with call-to-action buttons
2. **About** - Designer bio with portfolio statistics
3. **Skills & Services** - 6 key service areas with skill proficiency indicators
4. **Projects** - Gallery of 6 sample design projects with categories
5. **Contact** - Contact information and working contact form
6. **Footer** - Navigation links and copyright information

## 🚀 Getting Started

### View Live Site
Visit: **[https://gabrieloladipo.github.io/Dabar/](https://gabrieloladipo.github.io/Dabar/)**

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/gabrieloladipo/Dabar.git
   cd Dabar
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## 🔧 Configuration

### Contact Form Setup (Formspree)

The contact form is integrated with **Formspree** for handling email submissions:

1. Visit [formspree.io](https://formspree.io)
2. Sign up and create a new project
3. Replace the form endpoint in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Customization

Edit the following in `index.html`:

- **Name & Branding**: Search for "Dabar Designs" and replace with your name/brand
- **Contact Email**: Update `hello@dabardesigns.com`
- **Projects**: Modify the project cards in the Projects section
- **Skills**: Update skill descriptions and proficiency percentages
- **Colors**: Edit CSS variables in the `:root` selector
  - `--blue`, `--accent`, `--text`, etc.

### Colors Reference
- Primary: `#3b82f6` (Blue)
- Accent: `#8b5cf6` (Purple)
- Background: `#0a0f1c` (Dark)
- Text: `#e2e8f0` (Light)

## 📱 Responsive Breakpoints

- Desktop: Full layout
- Tablet (900px): Single column with optimized spacing
- Mobile (768px): Stacked layout, hamburger menu

## 🎯 Fonts

- **Headings**: Space Grotesk (Google Fonts)
- **Body**: Inter (Google Fonts)

## 📊 Performance

- Lightweight HTML with embedded CSS and JavaScript
- Optimized animations using CSS transitions
- No external dependencies (except Google Fonts)
- Fast load time and smooth scrolling

## 🔐 Privacy & Security

- No cookies or tracking (unless you add analytics)
- Form submissions go directly to your email via Formspree
- All code is client-side (no backend needed)

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **Vanilla JavaScript** - Interactive features (no frameworks)
- **Google Fonts** - Typography
- **Formspree** - Contact form handling

## 📈 SEO Meta Tags

The site includes optimized meta tags for search engines:
- Meta description
- Viewport settings for mobile
- Open Graph tags (ready to configure)

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio!

## 📄 License

© 2026 Dabar Designs. All rights reserved.

---

**Need help?** Open an issue or check the source code for detailed comments.
