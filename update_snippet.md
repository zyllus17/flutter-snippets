1. Increment the version number in `package.json` file and check if all snippets are mentioned in `contributes`.
2. Update the `README.md` with the new snippet names.
3. Update the `CHANGELOG.md` with the changes.
4. You must have `npm` installed on the system. Run `npm` in terminal to check.
5. Open terminal and type the following commands
- `npm install -g vsce`
- `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass`
- `vsce package`
6. The command will create a `.vsix` file.
7. Open this [link](https://marketplace.visualstudio.com/manage/publishers/marufhassan) and click on the three dots on the Extension you want to update and press Update.
8. Drop the .vsix file and your extension will be updated.