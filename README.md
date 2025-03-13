# zed-vercel-theme
The [Vercel](https://vercel.com) Theme, for [Zed](https://zed.dev)

## Light

![Vercel Light](./assets/vercel-light.png)

## Dark

![Vercel Dark](./assets/vercel-dark.png)

## How to update the extension

1. navigate to [extenstion.toml](./extension.toml) and bump version

2. Commit and push

3. Go to my Github fork of `extensions` from Zed, sync changes.

4. Open it locally, pull changes.

5. `cd extensions/vercel-theme`

6. Grab the commit hash of my push

7. `git fetch` and `git checkout <commit-hash>`

8. `cd ../../`, `git add .` and `git commit -m "Update submodule for Vercel Theme extension`

9. `git push origin main`

10. Create a pull request



## Acknowledgment

Made by converting this [VSCode theme](https://github.com/gantoreno/vscode-vercel) made by [@gantoreno](https://github.com/gantoreno) using [Zed theme importer](https://zed.dev/blog/user-themes-now-in-preview), and tweaking a few colors.
