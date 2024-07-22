# Website

[![Deploy to GitHub Pages](https://github.com/opslabhqx/pages-docusaurus-template/actions/workflows/deploy_github_pages.yml/badge.svg)](https://github.com/opslabhqx/pages-docusaurus-template/actions/workflows/deploy_github_pages.yml)

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

The site is automatically deployed using GitHub Actions. The output is available at [https://opslabhqx.github.io/pages-docusaurus-template/](https://opslabhqx.github.io/docs/pages-docusaurus-template/).

### Local Development

The website is set up to use GitHub Actions for continuous integration and deployment. To run the website locally for development, follow these steps:

1. **Clone the Repository**:
```bash
$ git clone https://github.com/opslabhqx/pages-docusaurus-template.git
$ cd docs
```

2. **Install Dependencies**:
```bash
$ npm install
```

3. **Start the Development Server**:
```bash
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

To generate the static content for the website:

```bash
$ npm run build
```

This command creates static content in the `build` directory, which can be served using any static content hosting service.

## License

This project is licensed under the [MIT License](/LICENSE). See the LICENSE file for details.
