# HNG-STAGE-1B

Accessible, responsive Profile Card built with semantic HTML, modern CSS, and vanilla JavaScript.

## Features

- Semantic structure using `main`, `article`, `header`, `figure`, `nav`, `section`, `ul`, and `li`
- Exact `data-testid` values for automated testing
- Live epoch time in milliseconds with `aria-live`
- Responsive layout for mobile, tablet, and desktop
- Accessible avatar image with meaningful alt text
- Keyboard-focusable social links with visible focus states
- Separate lists for hobbies and dislikes

## Project structure

- `index.html` — page markup and semantic layout
- `styles.css` — responsive styling
- `script.js` — live time updates

## How to run locally

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Use a local server

If you prefer running a local server, use any static server of your choice. For example:

```bash
python3 -m http.server 5500
```

Then open `http://localhost:5500` in your browser.

## Test IDs used

- `test-profile-card`
- `test-user-name`
- `test-user-bio`
- `test-user-time`
- `test-user-avatar`
- `test-user-social-links`
- `test-user-social-twitter`
- `test-user-social-linkedin`
- `test-user-social-github`
- `test-user-hobbies`
- `test-user-dislikes`

## Accessibility notes

- The avatar includes descriptive alt text.
- The social links open in a new tab and include `rel="noopener noreferrer"`.
- The current time is announced via `aria-live="polite"`.
- Focus styles are visible for keyboard users.

## Deployment

Add your hosted production link here after deploying to Netlify, Vercel, or GitHub Pages.

- Live URL: https://senatorcode.github.io/HNG-STAGE-1B/
- Repository URL: https://github.com/SenatorCode/HNG-STAGE-1B

## Submission checklist

- [x] Required content added
- [x] Required `data-testid` attributes added
- [x] Semantic HTML used
- [x] Responsive styling added
- [x] Accessibility basics covered
- [x] Live deployment link added
- [x] Final repo link added

## Notes

This repo intentionally avoids frameworks to match the task requirement of HTML, CSS, and vanilla JavaScript only.
