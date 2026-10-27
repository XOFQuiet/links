# Personal Link Landing Page

A clean, responsive, single-page links website inspired by micro-landing page platforms. Built with pure HTML and CSS, featuring smooth hover effects, social media branding, and a professional profile layout.

## Features

- Responsive design for desktop and mobile
- Clean and modern UI
- Profile section with avatar, name, and status badge
- Social media link cards
- Platform-specific hover effects and glow animations
- Lightweight with no frameworks required

## Built With

- HTML5
- CSS3
- Google Fonts (Inter)

## Customization

Update the following sections to personalize the page:

### Profile Information

```html
<h1 class="name">XOFQuiet</h1>

<p class="tagline">
    Tester • Developer • Researcher
</p>
```

### Profile Picture

```html
<img
    src="https://via.placeholder.com/200"
    alt="Profile"
    class="avatar">
```

### Social Links

Replace placeholder URLs with your own:

```html
<a href="https://github.com/yourusername" target="_blank" class="link-card github">
    <div class="link-title">💻 GitHub</div>
    <div class="link-sub">Projects & Code</div>
</a>
```

Add color to your own button:

```css
.github:hover{
    background:#24292E;
    color:#fff;
    box-shadow:
        0 0 20px rgba(36,41,46,.6),
        0 0 40px rgba(36,41,46,.3);
}
```

### Footer

```html
© 2026 XOFQuiet
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/XOFQuiet/links.git
```

2. Open `links.html` in your browser.

No build tools or dependencies required.

## Preview

The page includes:

- LinkedIn
- GitHub
- Instagram
- Facebook
- X (Twitter)
- YouTube
- Discord

## License

This project is open source and available under the MIT License.

---

Created with HTML & CSS.
