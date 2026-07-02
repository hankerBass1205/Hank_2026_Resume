# Hanker Lin - Resume Portfolio

This is a single-page, responsive resume portfolio website designed for Hanker Lin. It is built using HTML, CSS, JavaScript, and styled with Tailwind CSS (via CDN) for a clean, modern, and tech-oriented appearance.

## Features
- **Responsive Design**: Mobile, tablet, and desktop friendly.
- **Dark Mode Support**: Adapts automatically based on system preferences.
- **Modern UI**: Incorporates scroll animations, glassmorphism, and minimal aesthetics.
- **Easy Deployment**: Fully static, ready to be hosted on GitHub Pages without any build steps.

## How to Customize

### 1. Modifying Content
All the textual content is located inside `index.html`. Open the file in any text editor and search for the text you want to change.
- **About Me**: Search for `<section id="about">`
- **Skills**: Search for `<section id="skills">`
- **Experience**: Search for `<section id="experience">`

### 2. Changing Photos / Placeholders
Currently, placeholders from `placehold.co` are used. To replace them:
1. Place your images inside the `images/` folder.
2. Open `index.html` and locate the `<img>` tags.
3. Replace the `src` attribute with the path to your image (e.g., `src="images/profile.jpg"`).

### 3. Adding a New Project
1. Open `index.html` and locate `<section id="projects">`.
2. Copy one of the existing project card blocks (the `<div>` with `group` class).
3. Paste it within the grid layout.
4. Update the image `src`, title, description, tags, and modal ID.
5. Scroll down to the bottom of the file (before the script tags) and copy an existing modal (e.g., `<div id="modal-1"...`).
6. Paste it, change the `id` to match your new project, and update the modal content.

### 4. Modifying Colors
The theme colors are defined in the Tailwind CSS configuration inside the `<head>` of `index.html`.
```html
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#2563eb', // Change this hex code for a different primary color
                secondary: '#0f172a',
                accent: '#38bdf8',
            }
        }
    }
}
```

## How to Deploy to GitHub Pages
Since this project requires no build tools, deployment is straightforward:
1. Initialize a Git repository in this folder: `git init`
2. Add and commit all files: `git add . && git commit -m "Initial commit"`
3. Create a new repository on GitHub and push your code.
4. Go to your repository settings on GitHub.
5. Navigate to the **Pages** section on the left sidebar.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select the `main` (or `master`) branch and click **Save**.
8. Within a few minutes, your site will be live!
