# SchoolSaathi website

Landing page for SchoolSaathi, with the two live demos.

```
index.html              Landing page
assets/whatsapp-qr.png  WhatsApp QR code (opens wa.me/qr/LYNIQPO6GN5LE1)
demo/admin.html         Owner and accountant dashboard demo
demo/teacher-app.html   Teacher app demo
```

Everything is plain HTML and CSS. There is no build step.

## Put it live on GitHub Pages

1. On github.com, create a new **public** repository, for example `schoolsaathi`.
2. On the repository page, click **Add file → Upload files**. Drag in everything inside this folder (`index.html`, `README.md`, and the `assets` and `demo` folders), then click **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and click **Save**.
4. Wait a minute or two. The site will be at `https://<your-github-username>.github.io/schoolsaathi/`.

If the repository is named `<your-github-username>.github.io`, the site opens at `https://<your-github-username>.github.io/` instead.

## Use your own domain (optional)

To use a domain such as `schoolsaathi.pk`, open **Settings → Pages → Custom domain**, enter it, and follow GitHub's DNS instructions at your domain provider.

## Common edits

- **Price:** search `index.html` for `Rs 10,000`.
- **Phone / WhatsApp:** search for `923158327536` (WhatsApp links) and `0315-8327536` (shown text).
- **Email and portfolio:** search for `mohammadhunain83@gmail.com` and `hunain.online`.
- **WhatsApp QR code:** replace `assets/whatsapp-qr.png` with a new image of the same name.

The demos use sample data only. Nothing is saved, and every change resets when the page reloads.
