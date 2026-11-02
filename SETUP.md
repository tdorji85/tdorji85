# Cyber Cyan GitHub Profile — Setup

## 1. Create the profile repository
Create a **public** repository named exactly `tdorji997-cell` (same as your GitHub username).

## 2. Upload the files
Upload everything in this package to the repository root, preserving this structure:

```text
tdorji997-cell/
├── README.md
├── assets/
│   ├── coding-developer.gif
│   ├── circuit.gif
│   ├── terminal.gif
│   ├── wave.gif
│   └── core-3d.gif
└── .github/
    └── workflows/
        └── snake.yml
```

The `.github` folder is hidden in some file pickers. Make sure it is uploaded too.

## 3. Enable the contribution snake
1. Open the repository's **Actions** tab.
2. If prompted, enable GitHub Actions for the repository.
3. Open **Generate contribution snake**.
4. Click **Run workflow**.
5. Wait for the workflow to finish successfully. It publishes the snake images to the `output` branch.
6. Refresh your profile README after a minute or two.

The workflow also runs automatically every 12 hours and when you push to `main`.

## 4. View your profile
Visit https://github.com/tdorji997-cell

## Notes
- The snake uses your real GitHub contribution calendar; it does not create fake contributions.
- GitHub profile customization is displayed through the profile README. GitHub does not allow replacing its native profile interface.
- The stats and activity graph are third-party embeds and may occasionally be unavailable or rate-limited.
