# Free Utilities Online Docs

![Project Status](https://img.shields.io/badge/status-MVP%20in%20progress-yellow)
![Website](https://img.shields.io/badge/website-live-brightgreen)
![Docs](https://img.shields.io/badge/docs-Docusaurus-blue)
![License](https://img.shields.io/badge/license-MIT-green)

![WordPress](https://img.shields.io/badge/WordPress-21759B?logo=wordpress\&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript\&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3\&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-92003B?logo=elementor\&logoColor=white)
![ACF](https://img.shields.io/badge/ACF-Custom%20Fields-00B388)

![Tools Planned](https://img.shields.io/badge/tools%20planned-100%2B-blue)
![Tools Documented](https://img.shields.io/badge/tools%20documented-0-informational)
![UI Elements Planned](https://img.shields.io/badge/UI%20elements%20planned-100%2B-purple)
![Snippets Planned](https://img.shields.io/badge/snippets%20planned-6-orange)
![SEO Clusters](https://img.shields.io/badge/SEO%20clusters-in%20progress-lightgrey)

Public documentation for [Free Utilities Online](https://freeutilitiesonline.com): SEO architecture, WordPress structure, reusable PHP snippets, tool documentation and build notes for a growing utility website.

---

## What is Free Utilities Online?

**Free Utilities Online** is a free online tools website built around practical browser-based utilities organized into SEO-focused clusters.

The project is currently being built as a WordPress-based MVP using Elementor, ACF, custom PHP snippets, external CSS/JS files and reusable UI patterns.

This repository documents how the project is structured, how the website is being built, and which reusable ideas can be extracted from the process.

---

## Live Website

https://freeutilitiesonline.com

---

## What this repository is for

This is a public documentation repository.

It focuses on:

* SEO architecture
* Tool cluster planning
* WordPress structure
* Reusable PHP snippets
* Asset loading strategy
* Tool functionality notes
* UI component planning
* Build-in-public development notes

The goal is to document the process of building a scalable utility website, not to publish the full production codebase.

---

## What this repository is not

This repo does not include:

* WordPress core files
* Full production source code
* Database exports
* Elementor exports
* Hosting configuration
* Private credentials
* API keys
* Full JavaScript source for every tool
* Private business data

Selected snippets, simplified examples and reusable patterns may be shared when they are useful for other developers.

---

## Documentation Structure

The documentation is organized into the following areas:

### Project Introduction

* `docs/intro.md`

### Architecture

* `docs/architecture/seo-structure.md`
* `docs/architecture/wordpress-stack.md`
* `docs/architecture/asset-system.md`

### WordPress Snippets

* `docs/snippets/dynamic-sitemap.md`
* `docs/snippets/asset-loader.md`
* `docs/snippets/related-tools-shortcode.md`

### Tool Documentation

* `docs/tools/image-tools/exif-remover.md`
* `docs/tools/image-tools/image-compressor.md`
* `docs/tools/image-tools/image-metadata-viewer.md`

### UI Library

* `docs/ui-library/overview.md`

---

## Tech Stack

| Area                  | Stack                  |
| --------------------- | ---------------------- |
| CMS                   | WordPress              |
| Page building         | Elementor Pro          |
| Structured content    | Advanced Custom Fields |
| Backend customization | PHP snippets           |
| Frontend              | HTML, CSS, JavaScript  |
| Documentation         | Docusaurus             |
| Docs deployment       | GitHub Pages           |
| License               | MIT                    |

---

## Current Status

### Website

* [x] WordPress MVP started
* [x] Initial utility tools published
* [x] Initial SEO clusters defined
* [x] Custom navigation and footer implemented
* [x] Custom CSS system started
* [x] External CSS/JS loading approach started
* [ ] Full MVP completed
* [ ] Large-scale tool expansion
* [ ] Full UI consistency pass
* [ ] Technical optimization phase

### Documentation

* [x] Public GitHub repo created
* [x] MIT license added
* [x] README started
* [ ] Docusaurus installed
* [ ] GitHub Pages deployment configured
* [ ] SEO architecture documented
* [ ] Dynamic sitemap snippet documented
* [ ] Asset loader snippet documented
* [ ] Related tools shortcode documented
* [ ] Tool documentation expanded

### WordPress Snippets

* [x] Dynamic sitemap concept
* [x] Asset loader concept
* [x] Related tools shortcode concept
* [ ] Public documentation with placeholders
* [ ] Usage examples
* [ ] Customization notes
* [ ] Security notes

### UI Library

* [x] UI library concept defined
* [x] Component categories planned
* [x] 153 UI element subtypes planned
* [ ] UI elements documented
* [ ] Tool card patterns documented
* [ ] Form/input patterns documented
* [ ] Sidebar patterns documented
* [ ] Mobile-first patterns documented

---

## Why document this?

Building a utility website is not only about publishing tools.

It also involves:

* choosing the right URL structure
* grouping tools by search intent
* designing reusable templates
* avoiding duplicated CSS and JavaScript
* creating internal linking systems
* making WordPress more dynamic without overloading it with plugins
* documenting repeatable snippets and patterns

This repo is where those decisions are documented.

---

## Local Documentation Setup

This documentation site will use Docusaurus.

Install dependencies:

```bash
npm install
```

Run the local development server:

```bash
npm run start
```

Build the static site:

```bash
npm run build
```

Serve the production build locally:

```bash
npm run serve
```

---

## Deployment

The documentation site is intended to be deployed through GitHub Pages.

The final docs URL will be:

```txt
https://angelmrdev.github.io/freeutilitiesonline-docs/
```

---

## Contributing

This project is still in active MVP development, so the documentation structure may change frequently.

Useful contributions can include:

* fixing typos
* improving explanations
* suggesting better snippet documentation
* improving Docusaurus navigation
* adding examples
* improving SEO architecture notes
* adding diagrams or screenshots

---

## License

This repository is licensed under the MIT License.

See the `LICENSE` file for details.
