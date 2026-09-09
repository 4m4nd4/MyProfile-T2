# MyProfile-T2
Practicing HTML and CSS by creating a simple profile.

<img width="946" height="427" alt="image" src="https://github.com/user-attachments/assets/a0c9933d-55f7-4cf6-b93d-b5866ad4abf2" />

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

Used 'https://www.w3schools.com/css/css3_flexbox_container.asp' to help with configuring the flexbox.

Main difficulty:
I had a hard time identifying when I was supposed to use 'rem', 'auto', and sizing configuration in CSS.

Ex:
width: min(100% - 2rem, 1100px);
margin: 0 auto;
padding: 1rem 0;

