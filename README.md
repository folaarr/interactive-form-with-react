# 📝 Interactive Form With React

A simple React application that asks for your name and displays a personalized greeting.  
Deployed with **GitHub Pages** at:  
👉 [Live Demo](https://folaarr.github.io/react-note-taking-app/)

---

## 🚀 Features
- Input field to type your name.  
- Greeting message updates when you submit.   

---

## 📂 Project Structure
    interactive-form-with-react/
    ├── public/
    │ ├── index.html # Main HTML file
    │ └── styles.css # Global styles
    ├── src/
    │ ├── components/
    │ │ └── App.jsx # Main React component
    │ └── index.js # React entry point
    └── package.json


---

## ⚙️ Installation & Setup (Local)

1. Clone the repository:
   ```bash
   git clone https://github.com/folaarr/react-note-taking-app.git
   cd react-note-taking-app
   ```

2. Install dependencies:
    ```bash
    npm install
   ```

3. Run the app in development mode:
    ```bash
    npm start
   ```

4. Open in your browser:
    ```
    http://localhost:3000
    ```

## 🌐 Deployment (GitHub Pages)

This project is hosted on **GitHub Pages** at:  
➡️ [https://folaarr.github.io/react-note-taking-app/](https://folaarr.github.io/react-note-taking-app/)

### Deployment steps:

**1. Add the following to your `package.json`:**
```json
"homepage": "https://folaarr.github.io/react-note-taking-app"
```

**2. Install the GitHub Pages package:**
```
npm install --save gh-pages
```

**3. Add deploy scripts in `package.json`:**
```
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

**4. Run deployment:**
```
npm run deploy
```
This will publish the production build to the gh-pages branch, which GitHub Pages serves automatically.

## 📘 Code Overview

### `App.jsx`
Manages two states:
- `name`: stores current input value.  
- `headingText`: stores submitted value for display.  

Functions:
- `handleChange`: updates input as the user types.  
- `handleClick`: updates greeting text on form submission.  

### `index.js`
- Renders the `App` component inside the `root` div in `index.html`.  
- Imports global styles.  

### `index.html`
- Base HTML structure.  
- Loads Google Fonts + CSS.  
- Defines `<div id="root"></div>` where React mounts.  

### `styles.css`
- Global styling (background, form, buttons, typography).   

---

## 🛠️ Built With
- [React](https://react.dev/)  
- JavaScript (ES6+)  
- CSS  
- [GitHub Pages](https://pages.github.com/)  

