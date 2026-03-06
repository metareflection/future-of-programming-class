# Advanced Topics in Programming Languages
CS252R Advanced Topics in Programming Languages (Fall 2026)

## Running website locally

On mac, install Ruby 3.3 using rbenv (the system/homebrew Ruby 4.0 is not compatible with `github-pages`):

```bash
brew install rbenv
rbenv install 3.3.6
```

This project includes a `.ruby-version` file, so rbenv will automatically use Ruby 3.3.6. To build and serve the site:

```bash
eval "$(rbenv init - zsh)"
bundle install
bundle exec jekyll serve
```

The last command serves the website at `http://localhost:4000`.
