# Mint Money — Ask an Expert

Interactive mobile HTML prototype for submitting finance questions and tracking expert answers.

## Open the prototype

Open `index.html` in a browser. No installation or build is required.

For camera and microphone recording, use HTTPS hosting or localhost and allow the browser permissions. File upload and text input are available as alternatives.

## Included flow

- Feed Home entry point and introduction
- Step 1: choose Video, Audio, or Message
- Step 2: upload, record, or type the question and submit
- Confirmation with an optional second question
- My Questions dashboard with sample selection and publication states
- Published-answer preview with user attribution and voucher status

No topic, title, or display-name inputs are required.

## Upload to GitHub

1. Create or open your GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Commit the files.

To push using Git from this folder:

```sh
git init
git add .
git commit -m "Add Mint Money Ask an Expert prototype"
git branch -M main
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_REPOSITORY_URL` with the URL of your repository. For an existing repository, copy these files into its checkout and use its existing remote and branch.

## Publish using GitHub Pages

In the repository, go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.

## Prototype behaviour

Question details are stored in this browser's local storage. Media is held only for the current session. No files are uploaded to a backend, no questions are sent to experts, and no vouchers are issued. Sample dashboard entries are labelled as examples.

Google Fonts load when available; system fonts are used otherwise. All application CSS and JavaScript are included in `index.html`.
