# NSHS Class of 1996 Alumni Website

Public landing page for the North Stafford High School Class of 1996 alumni contact registry.

## Hosting

Enable GitHub Pages from the main branch, / (root). The site is buildless: index.html contains its CSS, JavaScript and three embedded images; .nojekyll disables Jekyll processing. The custom domain will be configured later as nshs96.godfathor.com.

## Forms and privacy

Registration and administrator contact buttons open the deployed Google Apps Script forms in dialogs, with a direct-link fallback. The form obtains a names-only roster from the private spreadsheet. Contact data and the registration password remain in the Google backend; neither is stored in this repository. There is no browser-local submission simulator in the production page.

The owner tested signed-out access, request storage and email notifications, registration saves, repeat replacements and timestamp preservation, and both embedded forms before this upload. Recheck them after enabling hosting.

Private backend source/configuration and project documentation are maintained separately in the Wolverines Alumni Google Drive folder. Never commit contact records, passwords, private spreadsheet exports or credentials here.
