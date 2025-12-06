# mypixelquest.github.io

Portfolio site for My Pixel Quest, built with Jekyll and deployed via GitHub Pages’ default builder.

## Local setup
1. Install Ruby (GitHub Pages currently supports Ruby 3.3.x).
2. Install dependencies:
   ```
   bundle install
   ```
3. Run locally:
   ```
   bundle exec jekyll serve
   ```
   The site will be available at http://localhost:4000.

## Content & configuration
- Update site metadata in `_config.yml` (`title`, `description`, `url`, social handles).
- Home content lives in `index.markdown`; About in `about.markdown`.
- Blog posts live in `_posts/` using the `YEAR-MONTH-DAY-title.markdown` format.

## Deployment
Push to `main` (or the branch configured in the repo settings). GitHub Pages will build with the `github-pages` gem so local output matches production. No extra CI step required.
