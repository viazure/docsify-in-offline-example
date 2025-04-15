# Docsify In Offline Example

> An example project demonstrating how to use Docsify in offline environments

English | [简体中文](zh-cn/README.md)

## Project Introduction

This is an example project that demonstrates how to use Docsify in environments without internet access.

For the origin and deployment instructions, please refer to the blog post: [Deploying Docsify in Offline Environment](https://viazure.cc/posts/development/deploying-docsify-in-offline-environment/).

## Features

This project incorporates the following practical functions and plugins, and synchronizes the latest resource files on a regular basis.

- Bilingual support (Chinese/English)
- [Dark/Light theme switching](https://github.com/boopathikumar018/docsify-darklight-theme)
- [Full-text search](https://docsify.js.org/#/plugins?id=full-text-search)
- [Code highlighting](https://docsify.js.org/#/language-highlight)
- [Automatic spacing between Chinese and English](https://github.com/sy-records/docsify-pangu)
- [Code copy to clipboard](https://github.com/jperasmus/docsify-copy-code)
- [Footnotes](https://github.com/sy-records/docsify-footnotes)
- [Alert boxes](https://github.com/fzankl/docsify-plugin-flexible-alerts)
- [File update time display](https://github.com/fzankl/docsify-plugin-flexible-alerts)
- [Collapsible sidebar](https://github.com/iPeng6/docsify-sidebar-collapse)
- [Image zooming](https://kingdido999.github.io/zooming/docs/#/)

## Partial Directory and File Structure

```bash
├── docsify-generate-sidebar.bat # Sidebar update script
├── docsify-start-server.bat     # Server startup script
├── assets/                      # Static resources directory
├── docs/                        # Documentation content directory
└── zh-cn/                       # Chinese documentation directory
```
