# OneTJ Website

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Official documentation website for [OneTJ](https://github.com/oierxjn/OneTJ) - Tongji University Student Service Client.

## Overview

OneTJ is a Flutter-based mobile application that provides a clean and focused experience for Tongji University students to view personal information and academic calendar content.

## Features

- **Unified Authentication** - OAuth 2.0 based Tongji University unified identity authentication system with automatic token refresh
- **Information Center** - Display student basic information (name, student ID, college, grade, etc.)
- **Course Schedule** - Fetch and display student course schedules with weekly view support
- **Academic Calendar** - Show current semester, week number, and other calendar information
- **Local Storage** - Securely cache authentication and user data using Hive database
- **Multi-language** - Support Chinese and English interface switching

## Documentation

This repository contains the documentation source for OneTJ, built with [VitePress](https://vitepress.dev/) and themed with [vitepress-theme-teek](https://teek.docsify.top/).

### Quick Start

```bash
# Install dependencies
pnpm install

# Start development server
pnpm docs:dev

# Build for production
pnpm docs:build

# Preview production build
pnpm docs:preview
```

## Project Structure

```
OneTJ-Website/
├── docs/
│   ├── .vitepress/     # VitePress configuration
│   ├── @pages/         # Custom pages
│   ├── public/         # Static assets
│   └── index.md        # Homepage
├── package.json
└── README.md
```

## Related Links

- **GitHub Repository**: [oierxjn/OneTJ](https://github.com/oierxjn/OneTJ)
- **Original Repository**: [FlowerBlackG/OneTJ](https://github.com/FlowerBlackG/OneTJ)
- **Tongji University API**: api.tongji.edu.cn

## Feedback

If you have any questions or suggestions, please feel free to [submit an issue](https://github.com/oierxjn/OneTJ/issues).

## License

MIT
