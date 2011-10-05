# MELPA

This is some elisp that helps for building Emacs packages based on
version control
repositories.

The `buildarchive` script will create an archive file in the
`archives/` folder with version corresponding to the newest revision
available.

Repositories are checked out to the `working/` directory.  

All metadata for building the packages is based off the git submodule
for the [`epkgs`][epkgs] repository generated by the
[emacsmirror][emacsmirror].

[emacsmirror]: https://github.com/emacsmirror/
[epkgs]: https://github.com/emacsmirror/epkgs


