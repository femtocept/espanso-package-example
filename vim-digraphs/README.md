---
package_name: "vim-digraphs"
package_title: "Vim Digraphs"
package_desc: "A package implementing the digraphs of vim."
package_version: "0.1.0"
package_author: "Bryan Mosher"
package_repo: "https://github.com/femtocept/espanso-package-example"
---
# vim-digraphs 
A package implementing most of the digraphs from vim-digraphs. To use, prepend the digraph with comma.

Example: The digraph for α is `a*`. Type `,a*` to type α.

## what did i leave out?

- The control characters from ASCII like Line Feed and Bell
- The control characters from Unicode like Padding Character and High Octet Preset

I could probably add them if there is a desire for that.

For the list of digraphs, read the [documentation of vim-digraph](https://vimhelp.org/digraph.txt.html)
