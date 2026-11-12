# OrderGuard approver page

The page an OrderGuard approver opens from the button in OrderGuard's emails, to approve or decline requests with one tap.

- Static HTML, hosted on GitHub Pages. No keys, passwords or personal data are in this repo.
- The private link looks like `https://rohantavargeri19-prog.github.io/OrderGuard-approver/#t=<token>`. The token sits after `#`, so it is never sent to GitHub; the page only sends it to OrderGuard's own server.
- Opening the page without a link from an email just shows "This link has expired".

Source of truth: `web/approver/index.html` in the main OrderGuard repo.
