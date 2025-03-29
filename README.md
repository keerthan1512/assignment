# Project Setup

This project was bootstrapped with Vite.

## Installation

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2.  Navigate to the project directory:

    ```bash
    cd <project_directory>
    ```

3.  Install the dependencies:

    ```bash
    npm install
    ```

## Usage

To start the development server, run:

```bash
npm run dev
```

Open your browser and navigate to the address provided in the console (usually `http://localhost:5173/`).

## Assumptions and Considerations

*   This project assumes you have Node.js and npm installed on your machine.
*   The project uses environment variables for configuration. Make sure to set up the necessary environment variables before running the project.
*   The project uses Tailwind CSS for styling.

## Deployment

This project can be easily deployed to free hosting services like Netlify or Vercel.

### Netlify

1.  Create a Netlify account at [https://www.netlify.com/](https://www.netlify.com/).
2.  Install the Netlify CLI:

    ```bash
    npm install -g netlify-cli
    ```

3.  Build the project:

    ```bash
    npm run build
    ```

4.  Deploy the project:

    ```bash
    netlify deploy --prod --dir=dist
    ```

### Vercel

1.  Create a Vercel account at [https://vercel.com/](https://vercel.com/).
2.  Install the Vercel CLI:

    ```bash
    npm install -g vercel
    ```

3.  Build the project:

    ```bash
    npm run build
    ```

4.  Deploy the project:

    ```bash
    vercel deploy --prod --prebuilt
    ```

Here is the deployment link:

[Deployment Link](https://assignment-mu-black.vercel.app/login)
