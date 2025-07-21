

```
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

Check version of theme and check build log to update dependencies in Gemfile

add bellow line to _config.yml to ensure posts appear if deploying to vercel
```
permalink: /:slug:output_ext
```

