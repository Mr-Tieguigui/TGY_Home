# Guiyao Tie Personal Homepage

This directory contains the personal academic homepage of **Guiyao Tie**, adapted from the `AcadHomepage` template and prepared for deployment on GitHub Pages.

## Current Setup

Completed:
- Basic profile configuration
- English homepage content
- Profile photo configured at `images/profile.jpg`
- Publication, award, and invited talk sections updated
- Dedicated image placeholder paths added for papers, awards, and talks
- Unused Google Scholar dynamic fetching script removed to avoid unnecessary requests

## Image Paths

Profile photo:
- `images/profile.jpg`

Paper figures:
- `images/papers/prompt-injection-tool-selection.png`
- `images/papers/self-correction-benchmark.png`
- `images/papers/badvla.png`
- `images/papers/learnercompass.png`
- `images/papers/safeagent.png`
- `images/papers/masking-watermarking-cooperative.png`

Award image:
- `images/awards/challenge-cup.png`

Talk image:
- `images/talks/zhipu-innovibe.png`

Replace these placeholder files with your actual images while keeping the same filenames.

## Recommended GitHub Pages Setup

Recommended repository name:
- `your-github-username.github.io`

Typical published URL:
- `https://your-github-username.github.io/`

## Deployment Steps

1. Create a new GitHub repository, preferably named `your-github-username.github.io`.
2. Upload all files in this directory to the repository root.
3. Open the repository on GitHub and go to `Settings -> Pages`.
4. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` and `/ (root)`
5. Save the settings and wait for GitHub Pages to publish the site.

## Files You Will Most Likely Edit Later

- `_config.yml`: site title, links, sidebar information
- `_pages/about.md`: biography, education, publications, awards, talks
- `images/profile.jpg`: profile photo
- `images/papers/`: publication figures
- `images/awards/`: award images
- `images/talks/`: talk images

## Local Preview

If Ruby, Bundler, and Jekyll are installed locally, run:

```bash
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000
```
