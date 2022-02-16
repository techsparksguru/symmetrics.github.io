# Start
This project has been taken from free Hydra jekyll theme
# Modified notes
- `bundle exec jekyll serve --host 0.0.0.0 --livereload`

# Gotchas
If running on Ruby 3.0 and get the error like `LoadError: cannot load such file -- webrick` , then do the following   (This is ONLY for local - github doesn't require this)

- `bundle add webrick`