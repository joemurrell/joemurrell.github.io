# joemurrell.github.io

Personal project portfolio website hosted on GitHub Pages.

## About

This is a GitHub Pages site showcasing my projects and work. The site is built with a simple HTML/CSS structure and can be enhanced with Jekyll themes if desired.

## Local Development

To view the site locally:

1. Clone this repository
2. Open `index.html` in your browser

For Jekyll development:
```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## Customization

### Update Your Information

Edit `index.html` to:
- Change the header title and description
- Add your actual projects
- Update links to your project repositories
- Modify colors and styling in the `<style>` section

### Jekyll Configuration

Edit `_config.yml` to update:
- Site title and description
- Social media links
- Email address

## GitHub Pages Setup

This repository is configured for GitHub Pages. To enable it:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select the branch you want to deploy (usually `main`)
4. Save the settings
5. Your site will be available at `https://joemurrell.github.io`

## Adding Projects

To add a new project, copy one of the `.project-card` div sections in `index.html` and update:
- Project title (in the `<h3>` tag)
- Project description (in the `<p>` tag)
- Project link (in the `<a>` tag's `href` attribute)

## License

Feel free to fork and modify this template for your own use.