# you-are-here-test
Test repo for YouAreHere website frontend

## Development

If this is your first time, do Setup first

### Running locally

```rb
$ bundle exec jekyll serve
```

### Setup

1. Install Ruby

```sh
$ sudo apt install ruby-full build-essential zlib1g-dev
```

2. Install Jekyll

```rb
$ sudo gem install jekyll bundler
```

3. Test locally

If setting up for first time:
```rb
$ jekyll new --skip-bundle --force .
```

To install needed dependencies.
```rb
$ sudo bundle install
```

Running locally
```rb
$ bundle add webrick
```

## Content Updates

### Blog Posts

1. Create a new file under `_posts/`, making sure to follow the file naming conventions (start with date, followed, by approximate title, ending in `.md`).

2. In the new file, copy over the "front matter" from the other posts (Jekyll's term for the first few lines of a file, including the `---`s).

3. Update the "front matter" with information that matches your new post (updated title and date/time). Leave the layout and categories alone.
    - Make sure the date/time are not in the future, or the blog post will not appear until then.

4. Save and preview your update (described above under "Test locally").

5. Publish your update (described in the Git section)

### Site Pages

- To create a new page, create a new `[filename].md` file and copy over the "front matter" from the About page ("front matter" is Jekyll's term for the first few lines of a file, including the `---`s).

- Update the "front matter" with a new `title` and `permalink` which appropriately describe the new page.

- Save and preview your update (described above under "Test locally").

- Publish your update (described in the Git section)

### Git Instructions

Git is great because it allows you to make changes and undo changes without having to worry about backups.

1. Create a new file or update an existing file.

2. Add the update to the Git changes (called "staging" - `git add [filename]`).

3. Commit your staged changes, including a brief commit message describing the change (`git commit`).

4. Push the change to GitHub (`git push`).

### Tips

- [Customizing the site](https://jekyllrb.com/docs/themes/#overriding-theme-defaults)
- [Customizing Merlot theme specifically](https://github.com/pages-themes/merlot)
- Each custom layout should specify its parent layout in its header, likely until the parent is `default` (which is automatically supplied by the theme)
- "Front matter" on any pages (including blog posts) are really just metadata that Jekyll can use to perform sorting and content prefill/summary operations.
