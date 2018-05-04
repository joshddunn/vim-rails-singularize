# vim-rails-singularize

This plugin extends the singularize and pluralize functions in [vim-rails](https://github.com/tpope/vim-rails) since they don't work exactly the same as those as in rails. This plugin allows you to setup custom singularizing or pluralizing rules.

## Install

Make sure you install this plugin after [vim-rails](https://github.com/tpope/vim-rails).

    Plug 'tpope/vim-rails'
    Plug 'joshddunn/vim-rails-singularize'

## Singularize

    let g:rails_singularize = {
      "data": "datum"
    }

## Pluralize

    let g:rails_pluralize = {
      "datum": "data"
    }
