## ABBYY Checks

In this document, we will go over some checks that need to be applied for ABBY Finereader document so we do not have to do extra work down the line

- Italics text should be correct
- Greek text should be italics
- Ensure all `c.` in footnotes are italicized
- All parentheses are *not* italicized
- Make sure italicized `I` is not backwards slash
- Make sure `II` is not `IL`, `VI` is not `VL`
- Make sure there are no commas with spaces before " , ", " : ", and " ; "
- All footnote commentary that is not italicized has not italics
- Footnote citations where two titles are dilineated with `e`, make sure the `e` is not italics so it translates to `and` (also applies to capital `E`)
- Make sure footnote is not body format and vice versa
- Make sure footnotes that span accross multiple columns (and pages) are manually put on same line
- Remove hyphens
- Replace all `'` with `’`

## Final Checks

### Body Text
These are checks that should be executed manually *after* the work has been translated

- CTRL-F "of art" and "history of art" and see if it is not more appropriate to translate to "of the art"
- Make sure all footnotes have 1 footnote reference marker

### Footnotes
- Make sure to check for errors when running script: `IndexError` and `MISSING`
- Make sure there is a number after each `c.`, indicating a chapter
- Remove all extra `*`'s
- Make sure all " e " have been translated to "and" where appropriate
- Keep an eye out for longer footnotes, these often are problematic
- All non italic text is in english
- Make sure greek text is retained

