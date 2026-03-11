# IRAS Research Data Management Guidelines
This code creates a Quarto book containing the IRAS Research Data Management Guidelines. Once you have gained access to this repo, you can access the guidelines by clicking this link: https://UtrechtUniversity.github.io/iras-data-guidelines/.

## For developers
After you have cloned this repo via `git clone`, you can make adjustments to the guidelines and push them to this repo. Please check out https://quarto.org/docs/books/ for a quickstart on how to work with Quarto Books.

### Publishing locally
You can publish the guidelines locally by using the `quarto render --to html` command. This will render them to HTML format only (`quarto render` renders all formats, including e.g. PDF). The output will be written to the `_book` sub-directory of your project.

### Publishing externally
You can publish a Quarto website by using the `quarto publish gh-pages --no-browser` command. This is an easy way to publish locally rendered documents and websites. At the moment, the `--no-browser` option needs to be added because we're publishing a private website rather than a public one (the logic within `quarto publish` that waits for your site to be available before opening a browser won’t work correctly in this case).
