# Greenwood Library Website

This repository contains the codebase for the Greenwood Community Library website. The purpose of this project is to enhance the existing website by adding new features, such as a "Book Reviews" section and updating the "Events" page.

---

## Project Overview

### Existing Sections
The website initially included the following sections:
- **Home**
- **About Us**
- **Events**
- **Contact Us**

### Enhancements
The enhancements involved:
1. Adding a **Book Reviews** section.
2. Updating the **Events** page with new content.

---

## Workflow and Steps Taken

### Initial Setup
1. **Repository Creation**:
   - Created a repository named `greenwood-library-website`.
   - Initialized the repository with a `README.md` file.
   - Cloned the repository to the local machine.

2. **Adding Basic Files**:
   - Added the following initial files to the repository:
     - `events.html`
     - `contact_us.html`
   - Added random content to each of these files.
   - Staged, committed, and pushed the changes directly to the `main` branch to simulate the existing codebase.

---

### Contribution 1: Adding "Book Reviews" Section
1. Created a branch for the work named `add-book-review-morgan`.
2. Switched to the `add-book-review-morgan` branch.
3. Added a new file `book_reviews.html` to represent the "Book Reviews" section.
4. Added random text content to the `book_reviews.html` file.
5. Staged the changes:
   ```bash
   git add book_reviews.html
   ```
6. Committed the changes with a descriptive message:
   ```bash
   git commit -m "Add book reviews section."
   ```
7. Pushed the `add-book-review-morgan` branch to GitHub:
   ```bash
   git push origin add-book-review-morgan
   ```
8. Raised a Pull Request (PR) from `add-book-review-morgan` to the `main` branch.
9. Merged the PR to integrate the "Book Reviews" section into the `main` branch.

---

### Contribution 2: Updating the "Events" Page
1. Created a branch for this work named `update-events-jamie`.
2. Switched to the `update-events-jamie` branch.
3. Pulled the latest changes from the `main` branch:
   ```bash
   git pull origin main
   ```
4. Updated the `update_events.html` file with new content about upcoming community events.
5. Staged the changes:
   ```bash
   git add update_events.html
   ```
6. Committed the changes with a descriptive message:
   ```bash
   git commit -m "Update events page with upcoming community events."
   ```
7. Pushed the `update-events-jamie` branch to GitHub:
   ```bash
   git push origin update-events
   ```
8. Raised a Pull Request (PR) from `update-events-jamie` to the `main` branch.
9. Merged the PR to integrate the updated "Events" page into the `main` branch.

---

## Git Workflow Summary
- **Branching**: Created separate branches (`add-book-review-morgan` and `update-events-jamie`) for each task to ensure isolated development.
- **Commit Messages**: Used clear and descriptive commit messages to maintain repository clarity.
- **Pull Requests**: Raised and merged PRs after completing and reviewing each enhancement.

---

## Future Enhancements
1. Add dynamic features using JavaScript to improve interactivity.
2. Implement a backend system for storing and displaying book reviews dynamically.
3. Introduce a calendar widget for events scheduling.

---

## Authors
- **Morgan**: Added the "Book Reviews" section.
- **Jamie**: Updated the "Events" page with new content.

---

## How to Contribute
1. Fork the repository.
2. Create a branch for your feature:
   ```bash
   git checkout -b <feature-branch>
   ```
3. Commit your changes with clear messages.
4. Push your branch and raise a Pull Request.
```

You can now replace the content of your `README.md` file with this documentation. Let me know if you need additional refinements!
