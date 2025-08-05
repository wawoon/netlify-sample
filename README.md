# Netlify React Sample

This repository is a **minimal sample React application** that demonstrates how to:

1. Scaffold a project with **Create React App**.
2. Develop locally with Hot Module Reloading.
3. Build an optimized production bundle.
4. Deploy a static site to **[Netlify](https://www.netlify.com/)** with Continuous Deployment.

> The goal is to provide the very smallest amount of code and documentation required to get up and running on Netlify.  
> If you need the full Create-React-App reference, it is still available [here](https://create-react-app.dev/docs/getting-started/).

---

## Live Demo

A live version of this repo is automatically deployed on every push:  
👉 **https://netlify-react-sample.netlify.app**

*(The URL above may change for your own fork.)*

---

## Quick Start

### 1. Prerequisites

* [Node.js](https://nodejs.org/) ≥ v14
* [Yarn](https://yarnpkg.com/) or `npm`

### 2. Clone and Install

```bash
# Clone
$ git clone https://github.com/your-name/netlify-react-sample.git
$ cd netlify-react-sample

# Install dependencies
$ yarn        # or: npm install
```

### 3. Develop Locally

```bash
$ yarn start  # or: npm start
```

Open http://localhost:3000 to view the app. The page reloads when you make edits and shows lint errors in the console.

### 4. Build for Production

```bash
$ yarn build  # or: npm run build
```

The command creates an optimized bundle in the `build/` directory that is ready to be deployed.

---

## Deploying to Netlify

Netlify can publish the **`build/`** folder as a static site with no extra configuration.

### Manual Deploy

Install the Netlify CLI:

```bash
$ npm install -g netlify-cli
$ netlify deploy --dir build      # one-off deploy
```

### Continuous Deployment (recommended)

1. Sign in to Netlify and click **“New site from Git”**.
2. Select your Git provider and repository.
3. Use the default build command `yarn build` (or `npm run build`).
4. Set the publish directory to `build`.
5. Click **Deploy site**.

> Every push to `master` will now trigger a new build and deploy.

---

## Project Structure

```
netlify-react-sample/
├── public/          # Static public assets
├── src/             # React components & styles
│   ├── App.js
│   └── ...
├── package.json
└── README.md        # ← you are here
```

Feel free to adjust the structure to your own preference.

---

## Available Scripts

Inside the project directory you can run:

| Script | Description |
|--------|-------------|
| `start` | Runs the app in development mode on <http://localhost:3000>. |
| `build` | Bundles the app for production to the `build/` folder. |
| `test`  | Launches the test runner in watch mode. |
| `eject` | **Permanently** copies the configuration files and dependencies so you have full control. |

---

## Contributing

Found a bug or have a suggestion? Feel free to open an [issue](https://github.com/wawoon/netlify-sample/issues) or submit a pull request.

---

## License

[MIT](LICENSE)

---

## Acknowledgements

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

