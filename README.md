# Paal KP's Personal Website

This is my personal website built with Jekyll and hosted on GitHub Pages.

## About

Welcome to my corner of the internet! Here you'll find information about me, my projects, and ways to get in touch.

## Technologies Used

- Jekyll (static site generator)
- Minima theme
- Hosted on GitHub Pages

## Development

### Prerequisites

- Ruby (version 2.5.0 or higher)
- Bundler

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/paalkpandian/paalkpandian.github.io.git
   cd paalkpandian.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000`

### Building

To build the site for production:

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## Customization

- Edit `_config.yml` to change site settings
- Modify `index.md` for the homepage content
- Add new pages in the root directory or `_pages` folder
- Customize styles in `assets/main.scss`

## License

This project is released into the public domain under the [Unlicense](LICENSE).