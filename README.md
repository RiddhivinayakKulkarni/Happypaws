# Happypaws

A responsive pet food shop and adoption website, built with HTML, CSS, and JavaScript. Requires Node.js 18 or newer; no package installation is needed.

## Run

```sh
npm start
```

The server listens on port 3000 by default. Set `PORT` to choose another port.

## Check

```sh
npm run check
```

Features include dog/cat food filters, a shopping bag stored in the browser, quantity controls, and adoption profile dialogs. Products and pets are sample data. Payments, order processing, and adoption applications are not connected. Images are served from Unsplash and fonts from Google Fonts, with local font fallbacks.

## Static hosting

The site also runs on static hosting without Node.js. Publish `index.html`, `styles.css`, and `app.js` together in the same folder. Relative asset paths support hosting at a subdirectory such as GitHub Pages.

For a manual deployment on a service such as Netlify, upload the static site folder or its ZIP. No build command is needed. Publishing the Codex development environment is separate from deploying this website.
