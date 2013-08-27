New Rails project sandboxed using Bundler and rbenv
=====

```bash
mkdir project_folder
cd project_folder
rbenv local ruby_version
bundle init

# Add (or uncomment) 'gem "rails"' into Gemfile

bundle install --path vendor/bundle
rbenv rehash
bundle exec rails new .

# When rails asking, override Gemfile

# Project creation is done!
```
