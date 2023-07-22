# ipd-archive

Web archive for IPD articles from past conferences

## Note on Copyright

Individual authors retain the copyright to their work. Uncredited text is copyright 2021-2023 Model United Nations Development Organization (MUNDO).

Copyright for other works in this repo (images in particular) may be held by others and are used here under the Fair Use doctrine: the content is for educational purposes, has not been modified, is used to illustrate newly created content, and is not used for monetary gain.

## Contributions

Annual conference archives can be contributed by creating a new directory named with either the 4-digit year of the conference (2022) or, in the case of multiple conferences in a calendar year, the roman numerals plus 2-digit year (XIX23).

The SimplyStatic plugin for WordPress can generate the contents of this folder as static HTML pages with relative links. Links to internal URLs should be relative to the root directory and start with the name of this repository followed by the appropriate conference archive directory such as `/ipd-archive/2022/path/to/file.html`. You should specify the relative path in the plugin settings as beginning with `/ipd-archive/2022/`.

We use GitHub Pages to serve the entire repository as a website. GitHub automatically converts Markdown to HTML and supports custom HTML, CSS, and JavaScript.

Note that WordPress uses a URL convention on js and css files that is not compatible with the way files linked on GitHub Pages. WordPress appends a version string like `` to these source URLs. Before pushing a new archive, users should remove these strings to ensure that the CSS and JS files are loaded properly. The regex `\?ver=\d+(\.\d+)*` can be used to find most numeric version strings and remove them.

## To Do
 - archive 2023 articles
