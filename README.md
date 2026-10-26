# Research Solution website

A single-page website. Everything (design, photos, scripts) is inside `index.html`, so there is nothing else to install or build.

## Put it online for free (GitHub Pages)

1. Sign in at github.com and click **New repository**.
2. Name it exactly `YOURUSERNAME.github.io` (replace YOURUSERNAME with your GitHub username). Keep it **Public** and click **Create repository**.
3. Click **uploading an existing file**, then drag in `index.html` (and this README if you like). Click **Commit changes**.
4. Open **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait 1 to 3 minutes. Your site is live at `https://YOURUSERNAME.github.io`.

To update the site later, open the repository, click `index.html`, then the pencil icon (or upload a new copy with the same name) and commit.

## Change your details

Open `index.html` in any text editor and search for **EDIT YOUR DETAILS HERE** (near the bottom). You can change:

- your papers and profile links
- each team member's name, role, bio, research interests, publications, links and quote

## Reviews section

The "Reviews" section is hidden. When you have real client feedback (with permission), search for `id="reviews" hidden` and delete the word `hidden`. Replace the placeholder text with the real review. The "Reviews" link then appears in the menu automatically.

## Notes

- The WhatsApp number is used inside links only and is never shown on the page.
- Only publish a client's feedback or work with their permission.
