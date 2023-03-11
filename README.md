# you-are-here-test
Test repo for YouAreHere website frontend

## Development

If this is your first time, do Setup first

### Running locally

```rb
bundle exec jekyll serve
```

### Setup

1. Install Ruby

```sh
sudo apt install ruby-full build-essential zlib1g-dev
```

2. Install Jekyll

```rb
sudo gem install jekyll bundler
```

3. Test locally

If setting up for first time:
```rb
$ jekyll new --skip-bundle --force .
```

To install needed dependencies.
```rb
$ bundle install
```

Running locally
```rb
bundle add webrick
```

### Tips

[Customizing the site](https://jekyllrb.com/docs/themes/#overriding-theme-defaults)
[Customizing Merlot theme specifically](https://github.com/pages-themes/merlot)
Each custom layout should specify its parent layout in its header, likely until the parent is `default`