# MyProfile-T2
Practicing HTML and CSS by creating a simple profile.

Reminders:
- noopener → prevents the new page from accessing the original page through 'window.opener'. This is a security feature when using target="_blank".
- noreferrer → prevents the browser from sending the original page's URL as the referrer to the new website. It also implies noopener in modern browsers.

Use it in the CSS of most of the projects:
/* Basic reset */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    min-height: 100vh;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #222;
    background: #f5f5f5;
}

