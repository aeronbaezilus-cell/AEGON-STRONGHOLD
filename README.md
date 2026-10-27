# The Link Keep (Windows app)

Electron wrapper around `index.html`.

## Get the .exe from GitHub
1. Create a new GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Push to `main`. Open the **Actions** tab, wait for "Build Windows app" to finish.
3. Open the run and download the **link-keep-windows** artifact (installer + portable `.exe`).
4. For a public download page: tag a release, e.g. `git tag v1.0.0 && git push --tags`. The .exe files attach to the Releases page.

## Build locally (Windows)
```
npm install
npm start        # run
npm run build    # makes dist/*.exe
```
