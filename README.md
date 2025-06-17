# anvizor-website

This repository contains the source for the Anvizor website.

## Overview

The project is a static site that can be served directly from the `public/` directory. All HTML, CSS and assets live inside that folder. You can view the site locally using any web server.

## Local development

1. Clone the repository and navigate into it.
2. Ensure the `public/` directory exists with the site files.
3. Start a simple HTTP server pointing at the `public/` folder. For example:

   ```bash
   python3 -m http.server 8000 --directory public
   ```

4. Open `http://localhost:8000` in your browser to preview the site.

## Deployment

The site is completely static so deployment simply involves copying the contents of `public/` to your preferred hosting provider. You can use any static host such as GitHub Pages or an S3 bucket. After uploading the directory, the site will be available from your hosting URL.

## License

This project is licensed under the [MIT License](LICENSE).
