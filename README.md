# Ali Ahmed Khan - Portfolio

Static portfolio site (HTML, CSS, JavaScript). No build step needed.

## Files
- `index.html` - the whole website
- `images/` - project screenshots

## Add a project
Open `index.html`, find `const P=[` and copy one block inside it. Put the screenshot in `images/` and set `img:'images/your-shot.jpg'` and `url:'https://your-live-link'`.

## Contact form
Messages are sent to aliahmedkhan2579@gmail.com through FormSubmit (`data-endpoint` on the form in `index.html`). After deploying, submit the form once yourself, then open the activation email FormSubmit sends to that inbox (check Spam too) and click the confirm link. If sending ever fails, the form falls back to opening the visitor's email app.

## Put it on GitHub
1. Create a new empty repository on github.com (for example `portfolio`).
2. Unzip this folder, then in a terminal inside it run:
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
   git push -u origin main
   (Or on the repo page choose "uploading an existing file" and drag the files in.)

## Deploy on Vercel
1. Go to vercel.com, sign in with GitHub, click "Add New Project".
2. Import the `portfolio` repository.
3. Framework Preset: "Other". Leave Build Command and Output Directory empty. Click Deploy.
4. Every push to `main` redeploys automatically. Your link will look like `https://portfolio-xxxx.vercel.app`.
