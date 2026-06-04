# Privacy Policy — Tally AU

_Last updated: 22 May 2026_

Tally AU ("the extension") is a personal and small-business finance tracker
that runs entirely in your browser. This policy explains what the extension
does and does not do with your information.

## The short version

Tally AU does not collect, transmit, sell, or share any of your data. There is
no account, no server, and no analytics. Your financial records never leave your
control.

## What data the extension stores

The extension stores the financial records you enter or import — transactions,
payees, accounts, categorisation rules, recurring rules, and your settings
(including business name and ABN if you choose to provide them).

This data is stored:

1. **Locally in your browser**, using IndexedDB, on the device you are using; and
2. **Optionally, in a folder you choose** on your own computer, as a single
   `ledger.json` file, if you enable folder storage in Settings. If that folder
   is managed by a third-party sync client (such as OneDrive or Google Drive),
   that client — not Tally AU — may copy the file to those services under your
   own account and that provider's terms. Tally AU itself never connects to,
   authenticates with, or transmits data to OneDrive, Google Drive, or any other
   online service.

## What the extension does NOT do

- It does not send your data to us or to any third party.
- It does not include analytics, tracking, advertising, or telemetry.
- It does not require an account or login.
- It does not read your browsing history or the content of web pages. The
  optional right-click "add as expense" feature only receives the text you have
  explicitly selected, and only when you click that menu item.

## Permissions the extension requests

- **storage** — to save your records locally in the browser.
- **contextMenus** — to add the optional right-click "add as expense" item.
- **alarms** — to post recurring transactions on schedule.
- **sidePanel** — to optionally dock Tally into Chrome's side panel when you ask
  for it via the in-app button. This permission only enables that UI affordance;
  it does not allow the extension to read your browsing or page content.

The File System Access API (used for the optional folder storage) prompts you to
choose a folder and grant permission explicitly; access can be revoked at any
time through your browser.

## Your control over your data

Because all data is local, you can delete it at any time by removing the
extension and deleting your `ledger.json` file. You can export your data to CSV
or PDF from the Reports tab at any time.

## Children

The extension is intended for adults managing their own or their business's
finances and is not directed at children.

## Changes to this policy

If this policy changes, the updated version will accompany the corresponding
release of the extension.

## Contact

For questions about this policy, contact the developer through the Chrome Web
Store listing for Tally AU.

---

_Tally AU provides general information to help you organise your records. It is
not tax or financial advice, and is not a substitute for advice from a
registered tax agent or accountant._
