# Yue Liu (Lydia) — Interactive Personal Portfolio

A photo-led, interactive personal site for job applications and recruiting. Built with static **HTML, CSS, and JavaScript**, using real personal images. No AI API, server, or database needed to run.

## Clickable features

- **At work / After hours**: change the photo, message and interest tags.
- **Project filter**: switch between all projects, things built and analytical work.
- **Project case study cards**: open a modal with the question, approach and result.
- **Life photo gallery**: click a photo, then use left/right arrows or keyboard arrows to browse.
- **中文 / EN**: one-click bilingual copy for major sections and project modals.
- Scroll progress bar, smooth navigation, subtle entrance animation and responsive mobile design.

## Customize with Jupyter

1. Install Jupyter if needed, or use your existing Python notebook environment.
2. Keep `Customize_And_Preview.ipynb`, `index.html`, `assets/` and `TripFlow_Case_Study.pdf` together in one folder.
3. Open the notebook, edit `SETTINGS`, `COLORS`, your email and your GitHub username.
4. Run the notebook cells from top to bottom. The generated `github_site/` folder is the GitHub-ready site. The notebook also builds `Yue_Liu_Lydia_GitHub_Ready.zip`.
5. Advanced editing: interactive behavior is in `<script>` at the bottom of `index.html`.

## Publish on GitHub Pages

1. Create a Public repository, such as `lydia-portfolio`.
2. Upload the **contents of** `Yue_Liu_Lydia_GitHub_Ready.zip` to the repository root (`index.html`, `assets/`, `TripFlow_Case_Study.pdf`). Do not upload a parent folder by itself.
3. Open **Settings → Pages → Deploy from a branch**, select `main` and `/(root)`, save.
4. Your URL will be `https://YOUR_USERNAME.github.io/lydia-portfolio/` (replace with your actual username).

## Before sharing

- These are **your real photos**. Keep only those you are comfortable making public.
- Confirm the email and GitHub username included in the footer.
- TripFlow is labeled as a team project, based on its `package.json` listing multiple authors.
- The Columbia × JBS Capstone is described as ongoing; it does not claim finished results.
- McKinsey automotive aftermarket work is labeled as a research collaboration/project, not an employment claim.
- Google Fonts improve the typography but the page still works with fallback fonts without them.



## Latest update — Education story

The interactive education section includes real UC Davis and Columbia photos, short business-to-AI narrative, Chinese/English translations, an expandable explanation, and clickable photos in the lightbox. In GitHub Pages keep all the files within `assets/` alongside `index.html`. Degree completion at Columbia is marked expected December 2026.


## Update: Why UC Davis → Columbia, and a real work presentation

The interactive education story now explains the business-focused B.S. in Managerial Economics at UC Davis and the choice to pursue an M.S. in Applied Analytics at Columbia in response to the rise of AI. The story is available in Chinese and English and expands on click.

An original Freudenberg project-presentation photo is featured in the experience section. Its public website asset is framed to **exclude potentially internal presentation content**. It can be opened in the same interactive photo gallery as the lifestyle images. If you prefer not to publish any workplace imagery, delete that section or replace the image.

## Latest education detail

Each education card now has short bilingual course tags: UC Davis (Economics, Econometrics, Marketing & Strategy) and Columbia (Machine Learning, SQL, Strategy & Analytics). The click-to-expand narrative also connects these skills to the decision to study AI.
