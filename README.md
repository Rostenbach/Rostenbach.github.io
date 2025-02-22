
# My GitHub Pages Site

This repository hosts my personal website built with React and deployed using GitHub Pages.

## Getting Started

Follow these instructions to set up and deploy your React app to GitHub Pages.

### Prerequisites

- Node.js and npm installed on your local machine. You can download them from [here](https://nodejs.org/).

### Setting Up the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/<your-username>.github.io.git
   cd <your-username>.github.io
   ```

2. **Create a React App**:
   Use Create React App to set up a new React application.
   ```bash
   npx create-react-app my-app
   cd my-app
   ```

3. **Build the React App**:
   Build the React app for production.
   ```bash
   npm run build
   ```

4. **Copy the Build Files**:
   Copy the contents of the `build` directory to the root of your GitHub Pages repository.
   ```bash
   cp -r build/* ../
   cd ..
   ```

5. **Commit and Push**:
   Add, commit, and push the files to GitHub.
   ```bash
   git add .
   git commit -m "Deploy React app to GitHub Pages"
   git push origin main
   ```

6. **Enable GitHub Pages**:
   - Go to the settings of your repository on GitHub.
   - Scroll down to the "GitHub Pages" section.
   - Under "Source", select "main branch" and click "Save".

### Access Your Site

Your site should be available at `https://<your-username>.github.io`.

## Built With

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Create React App](https://create-react-app.dev/) - Set up a modern web app by running one command

## Contributing

If you have suggestions or find any issues, please feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
