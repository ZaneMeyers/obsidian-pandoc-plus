# obsidian-pandoc-plus

Fork of [Obsidian Pandoc](./obsidian-pandoc-readme.md)
implementing various functionality that I think is helpful.
I would PR these, except they'd probably want me to squash commits
or some other made up thing.
Also I'm not emotionally prepared to be told no.

## New Features

### New Commands: "Copy As ..."

Inspiration:

* [Copy as HTML](https://github.com/jenningsb2/copy-as-html)
* [Copy Document as HTML](https://github.com/mvdkwast/obsidian-copy-as-html)

Neither are actively maintained.

## Planned Features

### New Export Format: Rich Text Format (.rtf)

For pasting to MS Office products,
which do not respect certain CSS attributes
(`background-color`, `text-decoration`).

## Known Issues

"Copy As ..." currently allows all the same formats as Oliver's "Export As ...",
which causes strange behavior for binary formats (.pdf, .docx, .pptx).
Not really an issue, simply refrain from doing that.
I'll fix it later.

## Contributing

See Oliver's [development.md](./development.md)

Markup content should utilize [semantic line breaks](https://github.com/sembr/specification).
If you submit a PR rewrapping _my_ text to sentences or n columns,
kindly provide your cell number so I can personally ask you where you get the nerve.
