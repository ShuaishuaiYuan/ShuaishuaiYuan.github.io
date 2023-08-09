# Shuaishuai's Personal Website

Power by [jekyll](https://jekyllrb.com/) and [minimal-mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Development

### rbenv

See https://stackoverflow.com/a/66379795/1035008 for details.

Install `rbenv` to manage ruby environment:

```
brew update
brew install rbenv
```

Install ruby version 3.0.3.

> Note: We could not install the latest version because of error:
> ```
> nokogiri-1.12.5-x86_64-darwin requires ruby version < 3.1.dev, >= 2.5, which is
> incompatible with the current version, ruby 3.1.0p0
> ```

```
rbenv install -l
rbenv install 3.0.3
rbenv global 3.0.3
```

Add to `.zshrc`:

```
eval "$(rbenv init -)"
```

### Build and Run

Install bundle packages:

```
bundle update
bundle install
```

Build and run site locally:

```
bundle exec jekyll serve
```
