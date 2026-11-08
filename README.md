# Portfolio site

A single-page portfolio for GitHub Pages. No build step.

## Files

- `index.html`: the whole site (styles are inside it)
- `images/`: put your pictures here
- `resume.pdf` (optional): the site has no resume button right now. To add one, put your resume here and add a link to it in the hero section of `index.html`.

## Images to add

| File name | What to put there |
|---|---|
| `images/reducer-housing.png` | SolidWorks render of the gear reducer housing |
| `images/keychain.jpg` | Photo of the finished keychain |
| `images/clevis.png` | Render or drawing of the balance bar clevis |
| `images/turtle-box.png` | Photo or render of the transport box |

Until a file exists, the page shows a hatched placeholder with its name. Keep each image under about 500 KB so the page loads fast.

## Fill in the yellow parts

Everything highlighted yellow on the page (`class="todo"`) is something only you know. Replace the text and delete the `<span class="todo">` tags around it. Search `todo` in `index.html` to find them all.

Also remove or fix any claim you cannot explain in an interview.

## Publish on GitHub Pages

1. Create a repository named `YOUR-USERNAME.github.io` (public).
2. Upload `index.html`, `README.md`, and the `images` folder.
3. In the repository, open Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

Put that link at the top of your resume.
