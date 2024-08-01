# Inline-style-basic-interaction-and-server-validation-form
A HTML form with inline styles CSS having basic interaction and server validation form with NodeJS

Here's a step-by-step guide to running your Node.js program with a specific directory structure and using `npm` commands:

### Step 1: Set Up Your Project Directory

1. **Create Project Directory**:
   - Open your terminal or command prompt and navigate to the location where you want to create your project directory.
   - Create a new directory and navigate into it:
     ```bash
     mkdir FormProject
     cd FormProject
     ```

2. **Initialize npm**:
   - Initialize an npm project to create a `package.json` file:
     ```bash
     npm init -y
     ```

### Step 2: Create Necessary Files and Folders

1. **Create Files and Folders**:
   - Create the `index.html` file and `server.mjs` file inside your project directory:
     ```bash
     mkdir public
     touch public/index.html server.mjs
     ```

2. **Add Dependencies**:
   - If you plan to use any npm packages like `express` or `chalk`, install them:
     ```bash
     npm install express chalk
     ```

### Step 3: Write Your Code

1. **Edit `index.html`**:
   - Navigate to the `public` folder and add your HTML content:
     ```bash
     cd public
     # Edit index.html with your preferred editor (e.g., VS Code)
     code index.html
     ```

2. **Edit `server.mjs`**:
   - Go back to the root directory and add your server-side JavaScript code:
     ```bash
     cd ..
     # Edit server.mjs with your preferred editor
     code server.mjs
     ```

### Step 4: Run the Program

1. **Run the Server**:
   - You can start your server using `node` by running:
     ```bash
     node server.mjs
     ```
   - Alternatively, you can add a script in your `package.json` to run it with npm:
     - Edit the `package.json` file to include a start script:
       ```json
       "scripts": {
         "start": "node server.mjs"
       }
       ```
     - Then, run the server using:
       ```bash
       npm start
       ```

### Step 5: Access the Form

1. **Open Your Web Browser**:
   - After running the server, open your web browser and navigate to `http://localhost:8000` (assuming your server is set to run on port 8000).

### Final Directory Structure


```
FormProject/
├── node_modules/       # Installed npm packages (generated by npm)
├── public/
│   ├── index.html      # Your form HTML file
│   └── background.jpg  # Background image for your form
├── package.json        # npm project configuration file
└── server.mjs          # Your Node.js server file
```
