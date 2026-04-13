# Profile-Website

This is a small static website build with Astro to create a personal website. This Website is inteded to display background information about me and to allow publishing projects and blog posts. It is based on the [Monolume theme](https://github.com/heshify/monolume/tree/main), the contact form runs with [Web3Forms](https://web3forms.com/), and it is deployed to GitHub pages under [this address](https://timwindecker.github.io/).

## Development

1. Clone this repo
2. Open with VS Code
3. Store environment variables (e.g. `WEB3FORMS_KEY`) in `.devcontainer/secrets.env` and add them as a secret to your GitHub repo when deploying as a page
4. Use the Dev Containers plugin to setup the development container
5. Start local server with `bun run dev --host 0.0.0.0`
