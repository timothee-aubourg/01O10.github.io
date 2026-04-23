# timothee-aubourg.github.io

Personal academic website of Timothee Aubourg, Postdoctoral Researcher at the Nuffield Department of Clinical Neurosciences, University of Oxford.

Live at: [https://timothee-aubourg.github.io](https://timothee-aubourg.github.io)

## Structure

```
_pages/       ← site content (About, Research, R&D, Publications, CV)
_data/        ← navigation config
_config.yml   ← site settings (name, bio, social links)
images/       ← profile photo and assets
files/        ← downloadable files (CV PDF)
assets/       ← CSS, fonts, JS
_sass/        ← stylesheets
_includes/    ← Jekyll layout partials
_layouts/     ← Jekyll page templates
```

## Local development

```bash
bundle config set --local path 'vendor/bundle'
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Built with

[Academic Pages](https://github.com/academicpages/academicpages.github.io) — a Jekyll template for academic websites.
