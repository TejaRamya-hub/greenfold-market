# Greenfold Market

A single-page demo shop with a login screen and a 30-section Practice Lab for test automation.
Everything lives in `index.html` (HTML, CSS and JavaScript). React and AngularJS load from a CDN.

## Run locally
Open the folder in VS Code, install the Live Server extension, right-click `index.html` and choose
"Open with Live Server". The page opens at http://127.0.0.1:5500/

## Direct URLs (add to the end of the site address)
- `#login` login screen
- `#shop-react` and `#shop-angular` shop views
- `#lab-basic-form`, `#lab-buttons`, `#lab-checkboxes`, `#lab-dropdowns`, `#lab-locators`,
  `#lab-dynamic-content`, `#lab-waits`, `#lab-tables`, `#lab-alerts`, `#lab-modals`, `#lab-iframe`,
  `#lab-shadow-dom`, `#lab-drag-drop`, `#lab-hover-menu`, `#lab-tooltip`, `#lab-file-upload`,
  `#lab-download`, `#lab-hidden-elements`, `#lab-scroll`, `#lab-windows`, `#lab-authentication`,
  `#lab-stale-element`, `#lab-dynamic-list`, `#lab-network-delay`, `#lab-flaky`, `#lab-keyboard`,
  `#lab-slider`, `#lab-date-picker`, `#lab-resizable`, `#lab-complex-dom`

Lab and shop links sign in as a guest automatically.

## Deploy
Push to the `main` branch of a GitHub repository connected to Netlify. Every push redeploys the site.
`netlify.toml` tells Netlify to publish the repository root and needs no build command.

## Note
Login is a demo. Accounts are stored in each visitor's own browser, not on a server.
