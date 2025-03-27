# DevOps Kathmandu Connect 2025

[![Hugo Site](https://img.shields.io/badge/Built%20with-Hugo-ff4088)](https://gohugo.io/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Official website for DevOps Kathmandu Connect 2025 conference

📅 **Event Website:** [https://devops-kathmandu.github.io/connect/](https://devops-kathmandu.github.io/connect/)  
ℹ️ **About the Event:** [https://devops-kathmandu.github.io/connect/about-event/](https://devops-kathmandu.github.io/connect/about-event/)


## Getting Started

### Prerequisites
- Hugo
- Git

<br>

### Setup environment
- Clone the repository

```sh
git clone https://github.com/devops-kathmandu/connect.git
cd connect
```

- Setup theme

```
cd themes && git clone https://github.com/DevOps-Kathmandu/hugo-theme-event.git event
cd ..
```

> Updating themes

```
# When theme updates are available
cd themes/event
git pull origin main
cd ../..
```

- Run the development environment

```
hugo server -D
```

- View the Site

Open your browser and navigate to the URL displayed in the terminal(usually http://localhost:1313/)

### Key Directories Explained

- **assets/** - Contains source files that Hugo processes via pipes (e.g., SCSS to CSS)
- **content/** - All content for your website in Markdown format
- **layouts/** - Custom HTML templates that override theme defaults
- **static/** - Files copied directly to the output directory without processing
- **themes/event/** - The theme containing base templates and styles
- **public/** - Contains the generated HTML site after building with Hugo

### Configuration

- **hugo.yaml** - Main configuration file defining site parameters, menus, etc.
- **i18n/** - Contains translation files for multi-language support

### Development Files

- **.github/** - Contains workflows for continuous integration and deployment
- **.gitmodules** - Manages the theme as a Git submodule

## Making Changes

1. Edit the content in the content directory
2. Add or modify data in the `data/` directory
3. The site will automatically rebuild when files are changed
