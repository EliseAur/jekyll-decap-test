# Jekyll and Decap CMS Site with Tailwind CSS

![jekyll-decap-test](images/readme-img.jpg)

Welcome to my Jekyll and Decap CMS site repository! This project uses Jekyll, a simple, blog-aware, static site generator, and Decap CMS, a content management system for static site generators. Tailwind CSS is used for styling the site. This repository is just for testing out development tools like Jekyll, Decap CMS and Tailwind.

### Live Demo:

- **Link:** Link-to-github-pages

## Table of Contents

- [Project Overview](##project-overview)
- [Prerequisites](##prerequisites)
- [Installation](##installation)
- [Building the site](##building-the-site)
- [Using Decap CMS](##using-decap-cms)
- [Deployment](##deployment)
  - [GitHub Pages](###github-pages)
  - [Netlify](###netlify)
- [Configuration](##configuration)
- [Contribution Guidelines](##contribution-guidelines)
- [License](##license)
- [Contact](##contact)

## Project Overview:

This site is built using Jekyll and styled with Tailwind CSS. It includes various plugins for enhanced functionality, such as jekyll-feed, jekyll-sitemap, and jekyll-seo-tag. The site also integrates Decap CMS for managing content.

## Prerequisites:

Before you begin, ensure you have the following installed:

- Ruby version 3.0.0
- Bundler: a dependency manager for Ruby
- Node.js and npm (for Decap CMS and Tailwind CSS)

## Installation:

To set up the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install the required gems:

```bash
bundle install
```

3. Install the required npm packages:

```bash
npm install
```

4. Run Jekyll and Tailwind CSS:

```bash
npm run start
```

Your site should now be running locally at http://localhost:4000.

## Building the site

To build the site without serving it, run:

```bash
npm run build
```

## Using Decap CMS

To use Decap CMS, navigate to /admin on your local server. The configuration is set to use git-gateway as the backend.

## Deployment

For deploying your Jekyll site, consider using services like GitHub Pages or Netlify.

### GitHub Pages

To deploy on GitHub Pages:

1. Uncomment the github-pages gem in your Gemfile:

```bash
gem "github-pages", group: :jekyll_plugins
```

2. Update the bundle

```bash
bundle update
```

3. Push the code to your GitHub repository. GitHub Pages will automatically build and serve your site.

### Netlify

For deploying on Netlify:

1. Connect your repository to Netlify.
2. Set the build command to npm run build.
3. Set the publish directory to \_site.

## Configuration

Key configuration settings can be found in \_config.yml. Here are some customizable settings:

- Site settings (title, email, description)
- Build settings (theme, plugins)
- Decap CMS configuration (backend, media folder, collections)
- Tailwind CSS configuration (tailwind.config.js)

## Contribution Guidelines

I welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For questions or support, please contact your-email@example.com.
