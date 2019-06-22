## Environment Setup

To make this repository work, you need to run the following installers on Windows

- `node.js` v10.0.x - Download it from <https://nodejs.org/en/>
- `yarn` - Download it from <https://yarnpkg.com/en/docs/install>

## Project Setup

Open your terminal (Use `cmd` on Windows), type the following to install libraries

```bash
  yarn install
```

Then start the development by issuing

```bash
  npm run start
```

## Add a new page

1. Create a new folder under `src/html`
2. Edit `gulpfile.js`, append the above `folder name` to `var blks`
3.
4. Edit `src/html/nav.html`, add a new page link with the same `folder name` just above this line `<!-- ADD YOUR NEW PAGE ABOVE -->`
