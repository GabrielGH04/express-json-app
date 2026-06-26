# Taco Town

<img width="1912" height="540" alt="image" src="https://github.com/user-attachments/assets/c18fe0d7-4b2b-4d50-9436-332994c9caf4" />

<img width="1912" height="701" alt="image" src="https://github.com/user-attachments/assets/78a329e6-cb3f-4e5d-b95e-7475a38c401b" />




A simple Express.js web app that lets you browse taco recipes parsed from a JSON data source. Pick a taco (chicken, beef, or fish) and the app displays its ingredients and toppings.

## Tech Stack

- **Node.js** / **Express.js** — server and routing
- **EJS** — templating
- **JSON** — recipe data source

## Getting Started

```bash
npm install
node index.js
```

Then open http://localhost:3000 in your browser.

## How It Works

- `GET /` — renders the home page
- `POST /recipe` — receives the user's taco choice and redirects back to `/` with the matching recipe data displayed
