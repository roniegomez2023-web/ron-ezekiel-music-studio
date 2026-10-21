RON EZEKIEL STUDIO PRO - Login refresh fix

Upload index.html to your existing GitHub Pages repository root, replacing the old index.html.
The current tab keeps the short-lived OAuth access token in sessionStorage, so a page refresh restores the channel.
Sign-in is required again after Google token expiry, opening a new tab/session, or clearing session data.
No refresh token or client secret is stored. Do not add third-party scripts to this site.
