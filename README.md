# A Little Something for Keira

A small, romantic flower garden website: falling petals, blooming roses and lilies, a hidden surprise, and a final bouquet. It is one self-contained file with no build step.

## Files

- `index.html` is the whole site (HTML, CSS and JavaScript together).
- The music is generated in the browser, so there are no audio files. The only outside request is Google Fonts (Pinyon Script, Cormorant Garamond, Jost), which falls back to system fonts if it is blocked.

## Put it online with GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html` and `README.md` to the root of the repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
5. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

Anyone with the link can open it, so share it only with the person you want to see it.

## Make it your own

Open `index.html` in a text editor and search for these:

- `Keira` to change the name (headline, button text and the final line).
- `Hey Keira, I made something for you...` for the opening line.
- `var QUOTE=` for the line revealed by the surprise button.
- `Made with a little extra thought` for the final message.

## Notes

- Music never autoplays. It starts only when the speaker button in the top corner is tapped.
- Animations are reduced automatically for people who have "reduce motion" turned on in their device settings.
