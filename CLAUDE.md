# claude-code-practice

## What this is

A one-page static site about what Ronben learned setting up Claude Code. The page is
`index.html`. Screenshots go in `images/`.

## How to preview

Open `index.html` in a browser, for example from the terminal:

```
open index.html
```

Or serve it locally and open http://localhost:8000:

```
python3 -m http.server 8000
```

## How it deploys

Vercel deploys the `main` branch automatically. There is no build step. Vercel serves
`index.html` from the repo root.

## Rules for this repo

- Plain HTML and CSS only. One `index.html` file plus the `images` folder. No frameworks,
  no JavaScript libraries, no npm, no build step.
- This repo is public. No secrets, no API keys, no client names or private client details.
- Work on a branch, never on `main`. Changes reach `main` through a pull request.
