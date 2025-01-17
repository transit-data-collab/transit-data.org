# transit-commons.org

Website for Transit Commons, a community of transit practitioners advancing open standards and technology through experimental projects.

## About Transit Commons

Transit Commons provides a community-governed space where transit practitioners can collaborate on emerging technologies and data standards, nurturing them until they're ready for broader industry adoption. While established institutions like APTA and MobilityData provide stable homes for industry standards, Transit Commons offers a middle ground where experimental ideas can flourish.

## Repository Structure

```console
.
├── src/                    # Source files
│   ├── _data/             # Site configuration
│   ├── _includes/         # Layout templates
│   ├── assets/            # CSS, JavaScript, etc.
│   └── *.md               # Content pages in Markdown
├── .eleventy.js           # 11ty configuration
├── .github/workflows/     # GitHub Actions deployment
└── package.json           # Project dependencies
```

## Local Development

1. Install dependencies:

    ```bash
    npm install
    ```

2. Start development server:

    ```bash
    npm start
    ```

The site will be available at `http://localhost:8080` with live reload enabled.

## Making Changes

1. Content pages are written in Markdown and located in `src/*.md`
2. Layouts and includes are in `src/_includes/`
3. Styles are in `src/assets/styles.css`
4. Site configuration is in `src/_data/site.json`

## Publishing Changes

1. Create a branch for your changes:

    ```bash
    git checkout -b your-branch-name
    ```

2. Make and commit your changes:

    ```bash
    git add .
    git commit -m "Description of changes"
    ```

3. Push to GitHub and create a Pull Request:

    ```bash
    git push origin your-branch-name
    ```

4. Once merged to main, GitHub Actions will automatically:

   - Build the site
   - Deploy to GitHub Pages
   - Make changes live at transit-commons.org

## Contributing

Transit Commons welcomes contributions from transit practitioners, developers, and innovators who want to advance transit technology. Whether you're fixing a typo, improving the design, or suggesting new content, your help is appreciated.

## License

AGPL-3.0-or-later
