# Personal Academic Homepage Template

This is a simple, purely static GitHub Pages project that does not require installation of dependencies.

## Document Description

- `index. html`: homepage content, modify name, introduction, paper, project, contact information.
- `Styles.css`: Page style, modify colors, spacing, fonts, etc.
- `Script.js`: Mobile navigation and year display.
- `assets/profile placeholder. svg`: Avatar placeholder map.
- `Assets/favicon. svg`: Browser tab icon.

## How to modify

1. Open 'index. html'.
2. Search and replace these placeholder contents:
    - `Name`
    - `Your Name`
    - ` your.email@example.com `
    - `github.com/yourname`
    - `Name of school or laboratory`
3. Copy your paper according to the template to the `Representative Paper` area.
4. If there is a personal photo, put it in `assets/`, such as `assets/profile. jpg`, and then put the following in `index. html`:

```html
<img class="profile photo" src="assets/profile placeholder. svg" alt="personal photo placeholder"/>
```

Change to:

```html
<img class="profile photo" src="assets/profile. jpg" alt="personal photo of name"/>
```

## Upload to GitHub Pages

Recommended method:

1. Create a new repository, and the recommended repository name is `your GitHub username. Github. io`.
2. Upload all the contents of this folder to the root directory of the repository.
3. Open the `Settings` -> `Pages` in the repository.
4. Select `Deploy from a branch` as the source.
5. Select `main` for Branch and `/root` for the directory.
6. Wait for 1-3 minutes before accessing `https://your GitHub username. github. io/`.

If you upload to a regular repository, you can also select the corresponding branch and directory in `Settings` -> `Pages`, and the access address is usually:

```text
Https://Your GitHub username. github.io/your repository name/
```

## Local Preview

Simply open 'index. html' with a browser to preview.
