# markdown-ext-pack

An extension pack suitable when interacting with Markdown

The `vsix` files can be downloaded [here](https://marketplace.visualstudio.com/items?itemName=NdagiStanley.markdown-ext-pack&ssr=false#version-history)

## Developer

### Updating process

1. Make changes
2. Commit changes
3. Update `CHANGELOG.md`
4. Update version in `package.json` (Format: `v<major>.<minor>.<patch>`)
5. Commit changes
6. Tag commit (Format: `v<major>.<minor>.<patch>`)
7. Push commits to remote
8. Push tag to remote (`git push origin <tag name>`)

### Undo

Delete tags:

- local tag - `git tag -d <tag name>`
- remote tag - `git push --delete origin <tag name>`

Unpublish:

- Extension version - Use the [web](https://marketplace.visualstudio.com/manage/publishers/ndagiSTANLEY)
- Extension - `vsce unpublish (publisher name).(extension name)`
