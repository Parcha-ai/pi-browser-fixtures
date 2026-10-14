# pi-browser-fixtures

Static pages for testing a browser agent: a one-step and a two-step sign-in, a two-factor setup page, a file upload that shows the file's SHA-256, a download link and a "prove you are human" button. They are the test fixture of [pi-browser](https://github.com/Parcha-ai/agentrun/tree/main/packages/pi-browser), and anyone can point their own agent at them.

**Do not enter real credentials.** Every page says so at the top. The sign-in pages accept any value, and nothing you type leaves your browser.

No data is collected. The site is static files on GitHub Pages. The pages' scripts run in your browser, send nothing anywhere and keep nothing past the tab.

Start at the index and follow the links. The pages are served without the `.html` extension.

The files here are synced from the pi-browser source and overwritten by each sync, so open an issue on the pi-browser repository instead of a pull request here. `SOURCE.json` names the commit and each file's SHA-256.

Apache-2.0, see `LICENSE`.
