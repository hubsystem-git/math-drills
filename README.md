# Math Drills

Timed math practice for iPhone, iPad and computers: addition, subtraction, multiplication, division, mixed practice and order of operations. High scores stay on each device.

## Put it online with GitHub Pages

1. Create a new repository on GitHub. Make it public, since GitHub Pages on a private repository needs a paid plan.
2. Upload everything in this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. On the repository page, choose **Add file → Upload files**, drag the files and the `icons` folder in, then **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, and click **Save**.
4. After a minute or two, the Pages settings show the app's address, such as `https://your-name.github.io/math-drills/`.

## Add it to an iPhone or iPad

1. Open the address in Safari.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open Math Drills from the home screen. It runs full screen and, after the first visit, works without an internet connection.

## Good to know

- **Scores live on each device.** The home-screen app keeps its own scores, separate from Safari, and removing the app from the home screen erases them.
- **Moving or saving scores:** on the home screen, tap **Copy backup code**, then paste the code into **Restore from a code** on the other device. You can also paste it into Notes to keep a copy. Restoring replaces that device's scores.
- **Sound** is off while the iPhone or iPad is in silent mode. The speaker button turns it off in the app too (M on a keyboard).
- **Updates:** after you upload a new `index.html` to GitHub, the app picks it up the next time it opens with an internet connection. GitHub can take up to 10 minutes to serve the new version.
- **On a computer** you can also double-click `index.html` to play. Installing and offline use need the GitHub address.

## Files

- `index.html`: the whole app
- `manifest.webmanifest`: the app's name and icon for the home screen
- `sw.js`: keeps the app working offline
- `icons/`: app icons
