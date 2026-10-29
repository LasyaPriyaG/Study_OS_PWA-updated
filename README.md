# Cherry Study OS PWA

A personal study planner and tracker designed to work as a Progressive Web App.

## Publish on GitHub Pages
1. Upload all files and the `icons` folder to the root of your `Study-OS_PWA` repository.
2. In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Open the published HTTPS URL in Chrome and choose **Install Cherry Study OS** from the address bar or Chrome menu.

## Planner updates
- The planner starts at **04:00** and runs through **01:00** the next morning.
- Tasks are attached to the week they were created in; each new week starts with an empty planner.
- Use **🕘 Previous weeks** to open saved weeks. Previous weeks are read-only so history cannot be accidentally changed.
- Existing tasks are retained and assigned to the week in which this updated version is first opened.

## Data and privacy
Planner tasks, notes, doubts, to-dos, and mistake logs are stored in this browser's local storage. File Vault items use local browser storage. Data is not automatically synced between devices, so keep your own backup if the data is important.

## Updates
The service worker caches the app shell for offline use and uses a versioned cache so new releases can replace older cached files.
