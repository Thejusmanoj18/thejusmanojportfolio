# Thejus Manoj — Game Developer Portfolio

A static portfolio website built with HTML, CSS, and vanilla JavaScript.

## Project structure

```text
thejus-game-developer-portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── images/   # Portfolio screenshots and renders
│   └── videos/   # Character showcase video
└── README.md
```

## Run locally

Open `index.html` in a browser. For a local web server, you can also run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy with GitHub and Vercel

1. Create a new GitHub repository (for example, `thejus-game-developer-portfolio`).
2. Upload the contents of this folder to the repository's **root**. Make sure `index.html`, `css`, `js`, and `assets` are all at the top level as shown above.
3. In Vercel, choose **Add New → Project**, import the GitHub repository, and deploy it.
4. Choose **Other** as the framework preset if Vercel asks. This is a static website, so no build command is needed. Set the output directory to `.` if Vercel requires one.

Vercel will use `index.html` as the website homepage. Keep the folder names and file paths unchanged so the images, video, CSS, and JavaScript load correctly.

## Updating the portfolio

- Edit page text and links in `index.html`.
- Edit appearance and responsive layout in `css/style.css`.
- Edit interactive behavior in `js/script.js`.
- Replace or add media in `assets/images/` and `assets/videos/`, then update the corresponding paths in `index.html`.
