# My Profile Page 👋

This is your personal profile website — a place to introduce yourself and show off
the projects you've built. It's built with plain **HTML, CSS and JavaScript**, the
same three languages you've been learning all term.

It comes with a light mode and a dark mode, works on phones and laptops, and has a
few small JavaScript features built in already. Your job now is to make it *yours*.

---

## 1. Find your files

You should have three main files:

| File | What it's for |
|---|---|
| `index.html` | The content of your page — your name, bio, projects, etc. |
| `style.css` | Colours, fonts, spacing — how everything looks |
| `script.js` | The interactive bits — dark mode, the mobile menu, and more |

Open `index.html` in your code editor to get started.

---

## 2. Replace the placeholder content

Everything in this template is placeholder content for a made-up student called
"Tejubabyface Aderogba." Search through `index.html` and replace:

- [ ] The page `<title>` and the description near the top
- [ ] Your name in the hero section (`<h1 class="hero-name">`)
- [ ] The tagline under your name — write it in your own voice
- [ ] Your initials in the avatar circle (`<span class="avatar-initials">`)
- [ ] The "About me" paragraph and quick facts
- [ ] Your skills list — remove anything you haven't learned yet, add anything you have
- [ ] Your **three real projects** — title, description, and the technologies you used
- [ ] Every GitHub link — replace `yourusername` and the repo names with your real ones
- [ ] Your email address in the contact section

**Tip:** use your editor's Find & Replace to swap every "Tejubabyface Aderogba" for your own name in one go.

---

## 3. Link your real GitHub projects

For each project card, you need two links:

```html
<a href="https://github.com/yourusername/your-repo-name" target="_blank" rel="noopener">View code</a>
<a href="https://yourusername.github.io/your-repo-name" target="_blank" rel="noopener">Live demo</a>
```

- **"View code"** should point to your project's GitHub repository.
- **"Live demo"** should point to your project running live, if you've turned on
  GitHub Pages for that repo. If a project doesn't have a live demo, you can
  delete that link.

Only have one or two finished projects? Delete the extra `<article class="project-card">`
block instead of leaving a fake one.

---

## 4. Try changing the theme colours

Open `style.css` and find the `:root` section near the top. These are **CSS variables**
— change a value once here and it updates everywhere on the page:

```css
--accent-coral: #ff8b6b;
--accent-sky: #5fd4f4;
--accent-sunshine: #ffcb5c;
```

Try swapping in your own favourite colours and see what changes. This is a great
way to make the theme feel like *your* profile instead of a template.

---

## 5. Put it on GitHub

1. Create a new repository on GitHub. If you name it `yourusername.github.io`
   (using your actual GitHub username), GitHub will publish it at the root of
   your GitHub Pages site.
2. Add these three files (`index.html`, `style.css`, `script.js`) to the repository.
3. Commit and push, just like you've done with your other projects.
4. In the repository's **Settings → Pages**, set the source to your main branch.
5. Wait a minute, then visit the URL GitHub gives you — your profile is now live!

---

## About the code (for the curious)

A few things worth knowing if you want to understand how this page works:

- The colours all live in CSS variables in `style.css`, so the whole theme can be
  restyled by changing a handful of values.
- `script.js` is split into six small, separately commented features — dark/light
  mode, the mobile menu, the typing effect in the hero, active-link highlighting
  as you scroll, the "copy email" button, and the footer year.
- Open your browser's DevTools console on the live page. There's a small message
  waiting for you there.

Have fun making it yours. 🚀
