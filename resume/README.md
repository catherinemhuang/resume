# Resume Site

A tiny static site that displays your resume PDF right on the page, with a download button.

## How to use it

1. Put your resume PDF in the `resume/` folder and name it `resume.pdf`
   (replacing the placeholder file there).
2. That's it — `index.html` already points to `resume/resume.pdf`.

## Folder structure

```
resume-site/
├── index.html      # the page — embeds the PDF + download button
├── style.css        # styling
└── resume/
    └── resume.pdf   # <-- replace this with your actual resume
```

## Publish it for free with GitHub Pages

1. Create a new GitHub repo (e.g. `my-resume`) and push these files to it.
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
4. After a minute, your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## Updating your resume later

Just replace `resume/resume.pdf` with a new file of the same name and push —
no code changes needed.
