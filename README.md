# Publish Snehpushp on GitHub Pages

This package contains only the finished website, including English and Marathi pages, the original logo, botanical images, and WhatsApp appointment links. It does not include the reference PDFs, secrets, or unrelated project files.

It is built specifically for the repository:
https://github.com/nikitadjadhav31/snehpushp

## Upload the website

1. Download and extract `snehpushp-github-pages.zip`.
2. Sign in to GitHub and open the repository above.
3. Use **uploading an existing file** on the empty repository screen, or **Add file → Upload files**.
4. Upload the extracted contents, including the `assets`, `images`, and `mr` folders. Put `index.html` directly at the repository root, not inside another folder. Do not upload just the ZIP file.
5. Commit the files to the `main` branch.

## Enable hosting

1. Open the repository's **Settings → Pages**.
2. Set **Source** to **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder, then click **Save**.
4. Wait for GitHub's deployment to finish. The Pages settings screen shows the published link and deployment status.

The expected website address is:
https://nikitadjadhav31.github.io/snehpushp/

The Marathi page is:
https://nikitadjadhav31.github.io/snehpushp/mr/

These addresses are not live until GitHub Pages has successfully deployed.

## Check after publishing

- Open both language pages and switch between English and Marathi.
- Confirm the clinic logo and botanical images appear.
- Confirm **Book an Appointment** opens WhatsApp for `+91 77580 25167` with a prefilled enquiry.
- Confirm the email link opens a message to `snehpushp.ayurveda@gmail.com`.

GitHub Pages currently offers free hosting for public repositories, subject to its terms and usage limits. It is not a guarantee of lifetime free service. Review its commercial-use restrictions for your clinic website: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

If you rename the repository, the website must be rebuilt for the new URL before uploading again.
