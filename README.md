# QA Agent

A lightweight, browser-based QA testing workspace built with **HTML, CSS, and JavaScript**. It is designed as a beginner-friendly project that can be uploaded directly to GitHub and hosted with GitHub Pages.

## Features

- Project dashboard and project-level separation
- Create and manage projects
- Generate starter test cases using predefined rules
- Mark test cases as **Pass** or **Fail**
- Add notes for failed tests
- Delete individual test cases
- Delete projects with confirmation
- View test status and execution history
- Filter test cases by project
- Export supported data as JSON or text
- Save workspace data in browser `localStorage`

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`

No framework, backend, API key, database, or build step is required.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For the best local development experience, you can also open the folder in Visual Studio Code and use the **Live Server** extension.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `qa-agent`.
2. Upload `index.html`, `README.md`, `.gitignore`, and `LICENSE`.
3. Open the repository's **Settings → Pages**.
4. Under the build/deployment section, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site; the URL will appear in the Pages settings.

## Important limitations

This is a **frontend prototype**. Test cases are starter scenarios generated from predefined rules. The app does not execute tests against a real website, inspect live APIs, run browser automation, or perform security scans. A Pass/Fail status is recorded when a user selects it; it is not an automatically verified result.

Workspace data is stored in the current browser's `localStorage`. It is not synchronized between devices or browsers. Clearing browser data may remove saved workspace information.

## Suggested next improvements

- Add automated browser testing with Playwright or Selenium
- Add a backend and database for shared workspaces
- Add authentication and role-based access
- Add CI integration and downloadable test reports

## License

This project is provided under the MIT License. See [LICENSE](LICENSE).
