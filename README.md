# VSCode Edi Support

A Visual Studio Code extension aimed at providing basic support for the EDI format.

## Features

![Quick Demo](docs/demo.gif)

- Basic syntax highlighting.
- Highlighting of parent segments.
- Basic tooltip.

## Requirements

None right now.

## Extension Settings

Nothing at this point.

## Known Issues

See below.

## TODO

- [ ] Status icon?
- [ ] Parsing of large files?
- [ ] Cache parsed results.
- [ ] Helper functions, e.g. splitting, segment lookup/jump-to, segment index jump-to, etc.
- [ ] Support other EDI formats aside from X12.
- [ ] Support multiple lines.
- [ ] Parse envelop headers for deliminator instead of using the hardcoded values of `>`/`*`/`~`/`^`.
  - Grammar wont like this though...

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...