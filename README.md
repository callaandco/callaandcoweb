# Calla & Co. website

A one-page static website for Calla & Co. weddings and ceremonies. It is a single `index.html` file with no build step.

## Before you publish

Open `index.html` in a text editor and replace everything in square brackets: names, bios, prices, contact details, photos and business registration details.

- **Photos:** the `images/` folder holds placeholders for the two team photos (`planner.svg` and `partner.svg`). Add your own photos as `planner.jpg` and `partner.jpg` in the same folder, then change `images/planner.svg` to `images/planner.jpg` (and the same for the partner) in `index.html`, and update the `alt` text.
- **Domain:** the `CNAME` file tells GitHub Pages to serve the site at callaandco.uk. Delete it if you decide to use a different domain.
- **Enquiry form:** replace `[FORM SERVICE URL]` with the address from a form service such as Formspree, so enquiries reach your email.

## Publish it free with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

To use your own domain, add it under **Settings > Pages > Custom domain**, then set up the DNS records GitHub shows you.
