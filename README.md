# Vlad-Petru Nitu

Personal website built with Jekyll and the [al-folio theme](https://github.com/alshedivat/al-folio). The site content lives in `_pages/about.md`; the CV PDF is in `assets/pdf/`.

## Preview locally

Install Ruby and the dependencies from `Gemfile`, then run:

```sh
bundle install
bundle exec jekyll serve --livereload
```

Open `http://localhost:4000`. Changes to the page and styles will reload automatically.

## GitHub Pages

The source repository is [vlad-nitu/vlad-nitu.github.io](https://github.com/vlad-nitu/vlad-nitu.github.io). It already exists, so no new repository needs to be created. Its previous `main` history is retained, with this site added as a new commit on top.

The GitHub Actions workflow builds the site and publishes the build artifact when `main` is updated. In the repository, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. To publish later edits, run:

```sh
git add .
git commit -m "Update website"
git push origin main
```

GitHub runs the build and deploys the new version. Follow progress under the repository’s **Actions** tab.
