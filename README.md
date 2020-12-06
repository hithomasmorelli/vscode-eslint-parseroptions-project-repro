# vscode-eslint-parseroptions-project-repro

Repository to reproduce issue described in [microsoft/vscode-eslint#1135](https://github.com/microsoft/vscode-eslint/issues/1135)

## Steps to reproduce issue

1. `git clone https://github.com/hithomasmorelli/vscode-eslint-parseroptions-project-repro.git`
2. `cd vscode-eslint-parseroptions-project-repro/functions`
3. `npm install`
4. `cd ..`
5. `code .`
6. Open the file `functions/.eslintrc.js` within VS Code
7. Enable vscode-eslint for the workspace
8. Wait a few seconds
9. `module` (on line 1 of `functions/.eslintrc.js`) should now be underlined in red, and there should be an error in the VS Code "Problems" tab
