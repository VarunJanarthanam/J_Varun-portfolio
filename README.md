# Varun Janarthanam — Portfolio Website

A responsive, animated portfolio website built with plain HTML, CSS, and JavaScript. It is designed to publish easily with GitHub Pages.

## Included sections
- Home / animated hero
- About
- Skills
- Projects (AI Production Planning and Sales Analytics)
- Resume download
- Contact links

## Run locally
1. Extract the ZIP file.
2. Open the `varun-portfolio` folder in VS Code.
3. Open `index.html` in your browser. For a convenient development workflow, use the VS Code **Live Server** extension and choose **Open with Live Server**.

## Personalize before publishing
Open `index.html` and replace:
- `YOUR-USERNAME` with your GitHub username.
- `YOUR-REPOSITORY` with each project's repository name.
- `YOUR-LINKEDIN` with your LinkedIn profile slug.
- `YOUR.EMAIL@example.com` with your professional email.
- Update the headline, bio, education, certifications, and skills to match your current resume.
- Replace the placeholder project descriptions with verified project details and add real screenshots/demo links when ready.

Copy your current resume PDF into `assets/` and name it `resume.pdf` (or change the link in the Resume section).

The Sales Analytics card is marked **In Progress**. Update its status, metrics, repository, and case study once the project is complete. Do not publish placeholder metrics as real results.

## Publish with GitHub Pages
1. Create a GitHub repository. For a user-site URL, name it exactly `YOUR-USERNAME.github.io`; alternatively use a normal repository and enable Pages in its settings.
2. Upload the contents of this folder (the `index.html`, `style.css`, `script.js`, and `assets` folder) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under the build/deployment settings, select **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save.
5. Wait for deployment and open the URL GitHub Pages displays. A user site is usually available at `https://YOUR-USERNAME.github.io/`.

## Notes
- This is a static site; it does not require a backend or database.
- Google Fonts are loaded remotely, so the page falls back to system fonts if they are unavailable.
- Use only public project links and information you are comfortable sharing.
