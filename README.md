# Rudhro Nil Mondal — Academic Website

A responsive, static academic portfolio built with HTML, CSS and a small amount of JavaScript. It is designed to be hosted free on GitHub Pages.

## 1. Preview locally

1. Extract the ZIP file.
2. Open `index.html` in a browser.

For a more realistic local preview, use the VS Code **Live Server** extension.

## 2. Add your photograph

1. Prepare a professional headshot (square or portrait orientation works best).
2. Copy it into the `assets` folder and name it `profile.jpg`.
3. In `index.html`, find:
   ```html
   <img id="profile-photo" src="assets/profile-placeholder.svg" alt="Profile placeholder for Rudhro Nil Mondal">
   ```
4. Change the `src` to `assets/profile.jpg` and update the alt text to `Portrait of Rudhro Nil Mondal`.

You can use `.png`, `.jpg`, or `.webp`; make sure the filename and extension match exactly.

## 3. Add your professional profile links

In `index.html`, search for `data-profile="scholar"`, `data-profile="linkedin"`, and `data-profile="orcid"`. Replace each `href="#"` with your actual public profile URL. Example:
- Google Scholar: `https://scholar.google.com/citations?user=YOUR_ID`
- LinkedIn: `https://www.linkedin.com/in/YOUR-PROFILE/`
- ORCID: `https://orcid.org/0000-0000-0000-0000`

Do not leave `#` in place once you know your profile URLs.

## 4. Publish using GitHub Pages (free)

1. Sign in or create an account at https://github.com/.
2. Create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io` (replace with your GitHub username).
3. Upload the contents of this folder to the repository's root. The `index.html` file must be at the root, not inside another folder.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the deployment to finish. Your site will be at:
   `https://YOUR-GITHUB-USERNAME.github.io/`

GitHub Pages is free for public repositories. GitHub may take a few minutes to publish the first deployment.

## 5. Updating the website

Edit `index.html` for text and links; edit `styles.css` for design changes. Upload the updated files to the same repository. GitHub Pages republishes the site automatically.

## Before publishing — please verify

- Add your photograph.
- Add your Google Scholar, LinkedIn and ORCID URLs.
- Check every publication title, author list, journal and DOI against the publisher record.
- Confirm the CV PDF is the version you want to make publicly downloadable.
- Consider whether you want your email address publicly visible. This version displays the email from your CV but does not publish your phone number or referees' contact details.
- Update the academic timeline if your programme dates or details change.

## Files

- `index.html` — website content and structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and current year
- `assets/` — CV PDF, favicon and profile-photo placeholder
