# Putting jellybean.io on GitHub Pages

This folder is the whole website: the page, the game, its pictures and fonts. GitHub Pages
hosts it free at an address like `https://your-name.github.io/jellybean-io/`.

Every file in it is under 25 MB, so you can upload it straight from the browser. You don't
need git or any other program.

## The first time

1. **Make a repository.** On github.com, sign in, press **New** (the green button), name it
   `jellybean-io`, keep it **Public**, and press **Create repository**.
2. **Upload the files.** On the new repository's page, click **uploading an existing file**.
   Open this folder on your computer, select **everything inside it** (`index.html`, the `art`
   and `fonts` folders, and the rest), and drag it all onto the GitHub page. Wait for the
   uploads to finish, then press **Commit changes**.
3. **Turn on Pages.** Go to the repository's **Settings → Pages**. Under **Build and
   deployment**, pick **Deploy from a branch**, then branch **main** and folder **/ (root)**,
   and press **Save**.
4. **Open it.** After a minute or two, the Pages settings show your site's address at the
   top. That's the link to share with your school.

## Updating it

Build a new version (`bash godot.sh pages`), unzip it, and upload the files again the same
way. GitHub replaces the old ones. The page updates within a couple of minutes; a player may
need to reload it once to get the new version.

## Good to know

- **Saves** live in each player's browser. Clearing browsing data clears them too.
- **Online play** (ONLINE in the game) needs a server; the page plays against bots. The
  desktop version can HOST a game for friends on the same network.
- **Blocked at school?** Some school networks block `github.io`. Ask whoever runs the network
  to allow your site's address.
- The game's two big files are stored gzipped (`index.wasm.gz`, `index.pck.gz`). The page
  unpacks them as they download. Keep them as they are.
