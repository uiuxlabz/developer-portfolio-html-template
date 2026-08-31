# DarkCV — Terminal Developer Portfolio

A dark, terminal-inspired developer portfolio template. Green-on-black aesthetic with typing animations, scan-line effects, and command-prompt motifs throughout.

## Design Distinction

**DarkCV** is not your average portfolio. It treats the entire site as a terminal session -- every heading is a command, every label a flag, every section a file being `cat`-ed. The typing animation cycles through real developer commands, skill bars animate on scroll like progress indicators, and the profile photo glows with an emerald halo. Built entirely with semantic HTML, custom CSS (no frameworks), and vanilla JavaScript.

### What Makes It Different

- **Terminal Aesthetic**: Every UI element uses monospace fonts, command-prompt prefixes (`$`, `>`), and code-block styling
- **Typing Animation**: Hero cycles through real developer commands (`hello.world()`, `npm run build`, etc.)
- **Scan-line Overlay**: Subtle CRT scan-line effect across the entire viewport
- **Green-on-Black**: Pure black (#0A0A0A) with lime green (#00FF88) accent, inspired by classic terminals
- **Code Snippet Overlays**: Project cards reveal code snippets on hover
- **Skill Progress Bars**: Terminal-style progress indicators with animated fill
- **Zero Dependencies**: No Bootstrap, no jQuery, no build tools -- just HTML, CSS, and JS

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Home — terminal hero, about, skills, projects, experience, testimonials, contact |
| `about.html` | About — detailed bio, personal info, skills breakdown |
| `projects.html` | Projects — filterable portfolio grid with code overlays |
| `contact.html` | Contact — terminal-style form with validation |

## Tech Stack

- **HTML5** — semantic markup, accessibility-first
- **CSS3** — custom properties, grid, flexbox, animations, no preprocessor
- **Vanilla JS** — Intersection Observer, typing engine, form handling
- **Fonts** — JetBrains Mono (display), Inter (body), Fira Code (code blocks)
- **Icons** — Font Awesome 6

## Getting Started

1. Open any HTML file in a browser -- no server required
2. Customize content by editing the HTML files directly
3. Replace images in `assets/img/` with your own
4. Edit `assets/css/base.css` to adjust colors, fonts, or spacing

## Customization

### Colors
Edit the CSS custom properties at the top of `base.css`:
```css
--bg-primary: #0A0A0A;
--accent: #00FF88;
```

### Typing Phrases
Edit the `phrases` array in `assets/js/main.js`:
```js
const phrases = ['hello.world()', 'console.log("dev")', ...];
```

## Structure

```
developer-portfolio-html-template/
  index.html
  about.html
  projects.html
  contact.html
  README.md
  assets/
    css/
      base.css
    js/
      main.js
    img/
      profile.jpg
      portfolio-1.jpg
      portfolio-2.jpg
      portfolio-3.jpg
      portfolio-4.jpg
      testimonial-1.jpg
      testimonial-2.jpg
      testimonial-3.jpg
```

---

Let's Build Something Together

[Contact me on Tally](https://tally.so/r/q4q1L9)
