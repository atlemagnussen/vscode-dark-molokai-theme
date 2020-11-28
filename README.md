# Molokai Sharp Theme for VSCode

This is a fork of [Dark Molokai theme](https://github.com/nonylene/vscode-dark-molokai-theme) with som additions from [Limelight Studios Dark](https://marketplace.visualstudio.com/items?itemName=limelightstudios.limelight-studios-dark) on C# specific hightlighting

Original colorscheme is inspired from [Molokai for Vim](https://github.com/tomasr/molokai) and official VSCode Dark Theme.

## Install

## Development

### Debug

- Open this project by vscode
- Press F5 to run extension
- Change theme to `Dark (Molokai)`

### Publish

Doc: <https://code.visualstudio.com/api/working-with-extensions/publishing-extension>

- Update commit hashes on comments
- Increment version on `package.json`
- Add changelog to `CHANGELOG.md`
- Publish with `vsce` command
- `git tag` with the new release

```console
$ vsce publish
```
