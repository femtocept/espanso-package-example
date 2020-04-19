---
package_name: "vim-digraphs"
package_title: "Vim Digraphs"
package_desc: "A package implementing the digraphs of vim."
package_version: "0.1.0"
package_author: "Bryan Mosher"
package_repo: "https://github.com/femtocept/espanso-package-example"
---

# vim-digraphs 

A package implementing most of the digraphs from vim-digraphs, themselves taken from the RFC1345 mnemonics. To use, prepend the digraph with comma.

Example: The digraph for α is `a*`. Type `,a*` to type α.

## general principles
(adapted from original helpfile)

To make it easy to remember the mnemonic, the second character has
a standard meaning:

| char name             | char  | meaning                           |
|-----------------------|-------|-----------------------------------|
| Exclamation mark      | !     | Grave                             |
| Apostrophe            | '     | Acute accent                      |
| Greater-Than sign     | >     | Circumflex accent                 |
| Question mark         | ?     | Tilde                             |
| Hyphen-Minus          | -     | Macron                            |
| Left parenthesis      | (     | Breve                             |
| Full stop             | .     | Dot above                         |
| Colon                 | :     | Diaeresis                         |
| Comma                 | ,     | Cedilla                           |
| Underline             | _     | Underline                         |
| Solidus               | /     | Stroke                            |
| Quotation mark        | "     | Double acute accent               |
| Semicolon             | ;     | Ogonek                            |
| Less-Than sign        | <     | Caron                             |
| Zero                  | 0     | Ring above                        |
| Two                   | 2     | Hook                              |
| Nine                  | 9     | Horn                              |
| Equals                | =     | Cyrillic (= used as second char)  |
| Asterisk              | *     | Greek                             |
| Percent sign          | %     | Greek/Cyrillic special            |
| Plus                  | +     | smalls: Arabic, capitals: Hebrew  |
| Three                 | 3     | some Latin/Greek/Cyrillic letters |
| Four                  | 4     | Bopomofo                          |
| Five                  | 5     | Hiragana                          |
| Six                   | 6     | Katakana                          |

## what did i leave out?

- The control characters from ASCII like Line Feed and Bell
- The control characters from Unicode like Padding Character and High Octet Preset

I could probably add them if there is a desire for that.

For the list of digraphs, read the [documentation of vim-digraph from
vim](https://vimhelp.org/digraph.txt.html#digraphs-default).
