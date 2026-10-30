# IYF S12 - Week 3 Assignment

## 🌐 Live Demo
You can view the live project here: [Live Website Link](https://gracesaigilu.github.io/iyf-s12-week-03-gracesaigilu/)

## 📁 Repository Overview
* `index.html` - Main HTML structure
* `style.css` - Custom styling
* `script.js` - JavaScript functionality
* `terminal-log.md` - Log of terminal commands
* `new-project.sh` - Automation script for creating project structures
#!/bin/bash
# Creates a new project with standard structure

PROJECT_NAME=$1

if [ -z "$PROJECT_NAME" ]; then
  echo "Usage: ./new-project.sh project-name"
    exit 1
    fi## Collaboration

* **Partner:** Partner did not participate
* **Pair Repository:** https://github.com/gracesaigilu/iyf-s12-week-03--pair-gracesaigilu
* **PR Opened:** https://github.com/gracesaigilu/iyf-s12-week-03--pair-gracesaigilu/pull/2
* **PR Reviewed:** N/A (Partner did not open a PR)
* **Merge-Conflict PR:** https://github.com/gracesaigilu/iyf-s12-week-03--pair-gracesaigilu/pull/2

> **Note on Partner Inactivity:** My assigned partner never took part in the lab. I completed my own branch, pull request, merge-conflict resolution, and rule bypass steps independently as per guidelines.


    mkdir -p "$PROJECT_NAME"/{src/{css,js,images},docs,tests}
    touch "$PROJECT_NAME"/README.md
    touch "$PROJECT_NAME"/src/index.html
    touch "$PROJECT_NAME"/src/css/styles.css
    touch "$PROJECT_NAME"/src/js/main.js

    echo "# $PROJECT_NAME" > "$PROJECT_NAME"/README.md
    echo "Project $PROJECT_NAME created successfully!"
    
