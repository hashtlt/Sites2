# Peterson's Tree Care website

Website for Peterson's Tree Care, Santa Barbara County, est. 1970. Owned and run by ISA Certified Arborist Peter Scott (WE-4180).

## What's in this folder

- `index.html`: the entire site in one file (home page, `#faq` page and `#consulting` arborist page)
- `img/`: photos, header video, logo seal and oak leaf
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `petersons-tree-care`.
2. Click **Add file → Upload files**. Drag in everything in this folder, including the `img` folder, then click **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then branch **main** and folder **/ (root)**. Click **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/petersons-tree-care/`.

### Use your own domain (petersonstreecare.com)

In **Settings → Pages → Custom domain**, enter `www.petersonstreecare.com`. Then, at your domain registrar, add a CNAME record for `www` pointing to `<your-username>.github.io`. GitHub's help page "Managing a custom domain for your GitHub Pages site" has the exact records. Turn on **Enforce HTTPS** once it's available.

## Editing the words

Download the repository, then open `index.html` from your computer by double-clicking it. An **Edit text / Save page** bar appears in the bottom-left corner. Click the text you want to change and type, then click **Save page**. Replace `index.html` in the repository with the saved file. The bar only appears when the file is opened from a computer, so site visitors never see it.

## Before going live

- The two forms (free estimate and consultation) only show a confirmation message. Connect them to email with a form service such as Formspree, Getform or Basin by adding its `action` URL to each `<form>`, or ask your developer to.
- Confirm the Google review link and the FAQ answers.
