# Debug and publish

- Open this project by vscode
- Press F5 to run extension
- Change theme to `Dark (Molokai)`

# Publish
- Increment version on `package.json`

## Visual Studio Code Marketplace
Doc: <https://code.visualstudio.com/api/working-with-extensions/publishing-extension>  
[market url](https://marketplace.visualstudio.com/vscode)
```console
$ vsce publish
```

## Open-VSX Registry
Doc: <https://github.com/eclipse/openvsx/wiki/Publishing-Extensions>  
[market url](https://open-vsx.org/)

Package and publish in one go
```sh
npx ovsx publish -p <token>
```