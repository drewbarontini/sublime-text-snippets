Sublime Text Snippets
=====================

> I'm a Vim user, but these are for teammembers and my occasional use of Sublime Text :)

Installation
------------

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User # Change path if you're using Sublime Text 2
git clone git@github.com:drewbarontini/sublime-text-snippets.git Snippets
```

### Git Submodule

If you already have your Sublime Text settings in a repo (such as dotfiles), then use a Git Submodule instead:

```bash
cd path/to/dotfiles
git submodule add git@github.com:drewbarontini/sublime-text-snippets.git path/to/Snippets
-> Commit the submodule addition
```

Usage
-----

All snippets are prefixed to prevent clashing with Sublime Text's autocomplete.

- **CoffeeScript**: `cf`
- **Haml**: `hm`
- **Sass**: `ss`

Once you type the prefix, you'll see the autocomplete list of snippets.

Updating
--------

Simple `cd` into the directory for your snippets and run `git pull`.
