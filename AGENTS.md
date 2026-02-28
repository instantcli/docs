# InstantCLI documentation

## About this project

- Documentation site for [InstantCLI](https://instantcli.com), built on [Mintlify](https://mintlify.com)
- InstantCLI turns any API docs URL into a production-ready CLI
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "CLI" not "command-line tool" or "command line interface"
- Use "your CLI" when referring to the user's generated CLI
- Use "API docs" not "API documentation" in casual usage
- Use "install command" not "install script" when referring to what users copy from the dashboard

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use `your-cli` as the placeholder command name in examples
- Use `your-slug` as the placeholder in install URLs

## Content boundaries

- Only document end-user functionality — not internal architecture
- Don't document the generation process internals
- Don't reference Mintlify platform features (this is InstantCLI docs, not docs about docs)
