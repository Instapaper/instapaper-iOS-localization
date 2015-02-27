Instapaper iOS Localizations
---

This repository tracks Instapaper's iOS translations, and we accept contributions for changes or additions to the translations.

Making a Contribution
---

Please do not use GitHub's web editor to make contributions. Because the files are encoded in UTF-16, GitHub recognizes the files as binary and messes up the encoding in the web editor. If you plan to make a contribution, please do the following:

1. Fork the repo on GitHub
2. Download the forked repo (using either ```git clone``` on the command line, the [GitHub Mac App](https://mac.github.com/), or the [GitHub Windows App](https://windows.github.com/))
3. Make your changes using a regular text editor (i.e. emacs, vim, nano), and not a rich text editor (i.e. Microsoft Word or TextEdit).
4. Commit your changes.
5. Create a pull request.

Viewing Diffs
---

This repository defines a ```.gitattributes``` file to let you view diffs for the translated files. In order to view the diff you must add the following to your gitconfig (```~/.gitconfig``` on *nix systems and Mac OS X):

    [diff "localizablestrings"]
        textconv = "iconv -f utf-16 -t utf-8"

Questions?
---

Please email [brian@betaworks.com](mailto:brian@betaworks.com).

