# NexaCorp ERP PWA - Project 3 An PWA

This is an AngularJS progressive web application adaptation of the Project 2 ERP dashboard.

## What is included
- AngularJS single page app with routes for Portal, Finance, Sales, CRM, Production, and Supply Chain.
- Reusable dashboard component for module pages.
- AngularJS CSV service that loads all dashboard data from CSV files.
- CSV files stored in `assets/data/`.
- Service worker and manifest for PWA install/offline support.
- Chart.js visualizations populated from CSV data.

## How to run locally
1. Unzip the folder.
2. Open a terminal in the project folder.
3. Run:
   ```bash
   npm install
   npm start
   ```
4. Open `http://localhost:8080`.

You can also use VS Code Live Server.

## Suggested GitHub Pages deployment
1. Create a GitHub repository.
2. Upload all project files.
3. In repository Settings > Pages, deploy from the main branch root folder.
4. Submit your deployed URL to Canvas.

## Video checklist
- Show the deployed site and navigate through all modules.
- Mention that the app is an AngularJS PWA.
- Show `manifest.webmanifest` and `sw.js`.
- Show `assets/data/*.csv` and explain that the interface is not hard-coded.
- Show `CsvService` and explain that it fetches/parses CSV files.
- Show the component files and routes.
- Show the app running in the browser.
