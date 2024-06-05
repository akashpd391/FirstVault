
# First Vault

## Overview

This repository contains my personal Obsidian vault named "First Vault" used to store private notes, journal entries, to-do lists, and other important information. Obsidian is a powerful knowledge base on top of a local folder of plain text Markdown files, making it an ideal tool for managing personal and project notes.

## Features

- **Note-taking:** Create and organize notes using Markdown.
- **Backlinks:** Automatically generate backlinks to see how notes are connected.
- **Graph View:** Visualize the structure and relationships between notes.
- **Tags and Links:** Organize notes with tags and internal links.
- **Custom Plugins:** Enhance functionality with community plugins.
- **Data Privacy:** All data is stored locally, ensuring privacy and security.

## Repository Structure
```bash
FirstVault/
├── DailyNotes/
│   ├── 2024-06-01.md
│   ├── 2024-06-02.md
│   └── ...
├── Projects/
│   ├── Project1/
│   │   ├── overview.md
│   │   ├── tasklist.md
│   │   └── ...
│   └── Project2/
│       ├── overview.md
│       ├── research.md
│       └── ...
├── Templates/
│   ├── daily.md
│   ├── project.md
│   └── ...
└── index.md


- `DailyNotes/`: Contains daily journal entries and notes.
- `Projects/`: Organized project-specific notes and documents.
- `Templates/`: Contains note templates for daily entries, projects, etc.
- `index.md`: The main index file linking to other notes.
```

## Installation

To set up the vault locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/akashpd391/FirstVault.git
    ```

2. Open Obsidian and set the vault directory to the cloned repository:
    - Open Obsidian.
    - Click on "Open folder as vault."
    - Navigate to and select the `FirstVault` directory.

## Usage

- **Creating Notes:** Use the "New Note" button in Obsidian to create new notes.
- **Linking Notes:** Use double brackets `[[note-name]]` to link to other notes.
- **Graph View:** Click on the Graph View to visualize connections.
- **Tags:** Use `#tags` to categorize and find notes quickly.
- **Templates:** Use predefined templates for consistency in note-taking.

## Customization

This vault includes several custom plugins and templates to enhance the note-taking experience. Customize these as per your needs:

- **Plugins:**
  - Calendar
  - Daily Notes
  - Backlink
- **Templates:**
  - Modify the templates in the `Templates/` folder to suit your style.

## Backup

Regularly push changes to GitHub to ensure your notes are backed up:

```bash
git add .
git commit -m "Update notes $(date '+%Y-%m-%d %H:%M:%S')"
git push origin main
```
**for Windows**
```bash
git add .
git commit -m "Update notes %DATE% %TIME%"
git push origin main
```

## License

This repository is private and contains personal notes. Unauthorized access, copying, or distribution of the contents is prohibited.
