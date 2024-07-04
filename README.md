# bug-publisher-spaces

This repo demonstrates a bug with the VSCode extensions when publisher field has spaces in it.
If publisher name has spaces, the VSCode won't be able to properly open extension settings using the default buttons.
See [microsoft/vscode-vsce/issues/1010](https://github.com/microsoft/vscode-vsce/issues/1010) for more info and discussion.

To reproduce:
1. Run `npx @vscode/vsce pack`
2. Install extension 
3. Navigate to the extension page
4. Click on "Settings" button
