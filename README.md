# Latent Minds

> **Measuring early childhood development from item-level responses**
> Dual Degree Project · IIT

A project webpage describing an unsupervised IRT-VAE framework for measuring child development across motor, cognitive, and social domains, using item-level data from the STREAM initiative (MDAT, DEEP, START).

---

## 🚀 Hosting on GitHub Pages

1. **Create a new repository** on GitHub (e.g. `latent-minds` or `<your-username>.github.io` for a user page).

2. **Add these files** to the repo root:
   ```
   index.html
   README.md
   static/
     └── pdfs/
         ├── report.pdf
         └── presentation.pdf
   ```

3. **Push the files**:
   ```bash
   git init
   git add .
   git commit -m "Initial webpage"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

4. **Enable Pages**:
   - Go to `Settings → Pages`
   - Under "Source", choose `Deploy from a branch`
   - Select branch `main` and folder `/ (root)`
   - Save

5. Your page will be live at:
   - `https://<your-username>.github.io/<repo-name>/` (project page)
   - or `https://<your-username>.github.io/` (if user page)

---

## 📁 Structure

```
.
├── index.html              # Main webpage (self-contained, CSS inline)
├── README.md
└── static/
    └── pdfs/
        ├── report.pdf      # Your full DDP report
        └── presentation.pdf
```

No build step. No dependencies. Just push and go.

---

## ✏️ What to customise

Open `index.html` and search for these to swap in your details:

| Find | Replace with |
|---|---|
| `Dual Degree Project · IIT · 2025` | Your specific institute / year |
| `static/pdfs/report.pdf` | Path to your actual report PDF |
| `static/pdfs/presentation.pdf` | Path to your slides PDF |
| Footer line | Add your name / advisor / lab if desired |

Optional additions you might want later:
- An **Authors** strip (with your name, advisor, affiliations) right above the buttons
- A **Figures** section with results plots
- **BibTeX** block for citations
- A link to **code** repository

---

## 🎨 Design notes

- **Typography:** Fraunces (display serif) + Inter (body) + JetBrains Mono (eyebrows/labels)
- **Palette:** Paper-warm background with terracotta accents — editorial / scholarly tone
- **No build tools:** single HTML file, CSS inline, only Google Fonts CDN
- **Responsive:** breakpoints at 820px and 480px

---

## 📄 License

Webpage built on top of the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), distributed under CC BY-SA 4.0.
