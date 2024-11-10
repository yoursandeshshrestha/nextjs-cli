# Basic Next App

A minimal boilerplate to quickly create Next.js applications with essential configurations like Tailwind CSS and a custom layout setup. This tool helps you get started with a pre-configured Next.js project without needing to set up a lot of initial configurations.

## Features

- Quick setup of a new Next.js project
- Automatically configures Tailwind CSS
- Adds a custom layout with basic file structure
- Removes unnecessary files from the default Next.js template

## Installation

You can either run the tool directly using `npx` or install it locally as a dependency.

### 1. Run with `npx`

You don't need to install anything globally. Just run the following command to create a new Next.js project with minimal boilerplate:

```bash
npx basic-next-app
```

This command will guide you through the project setup by asking for the project name and automatically setting up a new Next.js app for you.

### 2. Install Locally

If you want to install it as a dependency in your project, run:

```bash
npm install basic-next-app
```

Then, you can run the script with:

```bash
npx basic-next-app
```

## Usage

Once you've installed or run `npx basic-next-app`, follow the prompts to create a new Next.js project. You'll be asked for the project name (e.g., my-next-app), and it will automatically:

- Create a new Next.js application
- Clean up unused files (e.g., fonts and favicon)
- Add Tailwind CSS configurations
- Set up a custom layout file (layout.js or layout.tsx based on your TypeScript preference)

### Example Workflow

1. Run the following command:
   ```bash
   npx basic-next-app
   ```

2. Enter your project name when prompted:
   ```bash
   What is your project named? my-next-app
   ```

3. Navigate into the project folder:
   ```bash
   cd my-next-app
   ```

4. Run the Next.js development server:
   ```bash
   npm run dev
   ```

Your new Next.js app is now ready to be developed!

## Dependencies

This tool uses the following dependencies:

- **chalk**: For adding colored output in the terminal
- **execa**: For running commands in a child process
- **fs-extra**: For managing file operations
- **inquirer**: For asking questions in the terminal
- **ora**: For displaying spinner/loading indicators

## Contributing

1. Fork the repository

2. Clone your forked repo:
   ```bash
   git clone https://github.com/your-username/basic-next-app.git
   cd basic-next-app
   ```

3. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```

4. Make your changes and commit:
   ```bash
   git commit -am "Add new feature"
   ```

5. Push to your fork:
   ```bash
   git push origin feature-branch
   ```

6. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Next.js team for creating the Next.js framework
