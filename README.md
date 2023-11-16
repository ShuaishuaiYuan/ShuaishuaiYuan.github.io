# Shuaishuai's Personal Website

Power by [jekyll](https://jekyllrb.com/) and [minimal-mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Development

### rbenv

See https://stackoverflow.com/a/66379795/1035008 for details.

Check whether rbenv has been installed:

```
which rbenv
```


If haven't installed, install `rbenv` to manage ruby environment:

```
brew update
brew install rbenv
```

Install ruby version 3.1.0

```
rbenv install -l # check available versions
rbenv install 3.1.0
rbenv global 3.1.0
```

Add to `.zshrc`:

```
eval "$(rbenv init -)"
```

### Build and Run

Install bundle packages:

```
% gem update bundler ??
bundle update
bundle install
```

Build and run site locally:

```
bundle exec jekyll serve
```
