# Eko Geko

Eko Geko is a card-based educational game created by ECIU student ambassadors to promote sustainable innovation, teamwork, and collaboration.

This repository contains the source files and downloadable materials for the Eko Geko website.

## Website

The website is currently published through GitHub Pages:

[Visit the Eko Geko website](https://eko-geko.github.io)

A dedicated domain, such as `ekogeko.eu`, may be connected in the future. Changing to a custom domain will not require rebuilding the website or moving the repository.

## Repository structure

```text
Eko-Geko.github.io/
├── index.html
├── README.md
├── images/
│   ├── logo.png
│   └── game-photo.jpg
└── docs/
    ├── cards.pdf
    ├── rules.pdf
    └── teacher-guide.pdf
```

The actual contents may differ while the website is being developed.

## Updating the website

### Option 1: GitHub web editor

This is the recommended method for small text and file updates.

1. Open the repository in GitHub.
2. Open `index.html`.
3. Select the pencil icon to edit the file.
4. Make the required change.
5. Use **Preview changes** to inspect the edit.
6. Select **Commit changes** and enter a clear description.

When replacing a PDF, retain the existing filename if the website link should remain unchanged. File paths and filenames are case-sensitive on GitHub Pages.

### Option 2: VS Code

Use VS Code for larger changes or when a local preview is needed.

Clone the repository:

```powershell
git clone https://github.com/Eko-Geko/Eko-Geko.github.io.git
cd Eko-Geko.github.io
code .
```

Before editing, retrieve the latest version:

```powershell
git pull
```

Preview `index.html` using the **Live Server** extension by Ritwick Dey.

Publish changes:

```powershell
git status
git add .
git commit -m "Describe the change"
git push
```

GitHub Pages will deploy changes from the `main` branch.

## Adding downloads

Store downloadable files in the `docs` folder. A download link in `index.html` can use this format:

```html
<a href="docs/cards.pdf" download>Download Cards</a>
```

Check that:

- the file exists in the stated folder;
- the filename in the link matches the uploaded file exactly;
- uppercase and lowercase letters match;
- the link works in the local preview and on the published website.

## GitHub Pages limitations

The current site is intentionally simple. GitHub Pages is suitable for static pages, images, and downloadable files, but this project does not currently include:

- a visual content-management system;
- a server-side database;
- user accounts or personalised content;
- built-in contact-form processing;
- online registration, discussion, or game functionality;
- automatic editing of pages through a drag-and-drop interface.

Additional services or development would be needed if these features are required later.

## Collaboration and access

The repository belongs to the `Eko-Geko` GitHub organization.

- Organization owners manage access and repository settings.
- Student maintainers can update approved content and project materials.
- New contributors need a GitHub account and an invitation to the organization or repository.
- Significant structural changes should be reviewed before being merged into `main`.

## Copyright and licensing

Copyright in the game, illustrations, templates, and other materials remains with the relevant creators unless otherwise agreed in writing.

Do not assume that materials in this repository are available for commercial reuse or modification. A formal licence should be added when the creators and relevant ECIU representatives have agreed on the applicable terms.

## Acknowledgements

Created by ECIU student ambassadors, with support from ECIU staff involved in the development and dissemination of the initiative.

## Maintenance guide

A separate student maintenance guide is available for detailed instructions on browser-based editing, VS Code, publishing, troubleshooting, and project continuity.
