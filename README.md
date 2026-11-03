# PocketMine Tools

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](CHANGELOG.md) [![PHP](https://img.shields.io/badge/PHP-%3E%3D8.0-777BB4.svg)](INSTALL.md#requirements) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENCE)

A modern, bilingual (English and Persian) web toolkit for **PocketMine-MP** plugin developers. Built with PHP, vanilla JavaScript, and CSS—no framework or build step required

## Contents

- [Tools](#tools)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Documentation](#documentation)
- [Project structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Tools

| Tool | Description |
| --- | --- |
| **Form Creator** | Generate `SimpleForm`, `ModalForm`, and `CustomForm` code |
| **Plugin Creator** | Scaffold a plugin with folders and managers |
| **`plugin.yml` Creator** | Build commands and permissions |
| **`manifest.json` Creator** | Create Bedrock addon manifests with UUIDs |
| **MOTD Creator** | Preview Minecraft color codes and formatting |
| **Coordinates Converter** | Convert Overworld and Nether coordinates |
| **Command Creator** | Generate PHP command classes |
| **UUID Generator** | Generate deterministic, random, paired, or reversed UUIDs |
| **Dependencies Builder** | Configure `depend`, `softdepend`, and Virion dependencies |

## Features

- English and Persian interface with automatic language detection
- Dark and light themes
- Responsive layout
- Copy and download generated output
- Loader animation, Material Icons, and UI sounds

## Requirements

- PHP 8.0 or later (PHP 8.2/8.3 recommended)
- Apache or Nginx, or PHP's built-in development server
- JavaScript enabled in the browser

See the [installation guide](INSTALL.md) for server configuration and troubleshooting.

## Installation

1. Download or clone this repository.
2. Place the project in your web server's document root.
3. Configure the web server to serve `index.php` and allow the required routes.
4. Open the site in a browser and verify that the tools load correctly.

For complete instructions, including Apache, Nginx, shared hosting, and subfolder setups, read [INSTALL.md](INSTALL.md).

## Documentation

| Guide | Description |
| --- | --- |
| [Installation](INSTALL.md) | Requirements, deployment, configuration, and troubleshooting |
| [API reference](API.md) | JSON endpoints, request formats, and errors |
| [Contributing](CONTRIBUTING.md) | Coding standards and contribution workflow |
| [Changelog](CHANGELOG.md) | Version history and planned changes |
| [PocketMine-MP setup](docs/pocketmine-setup.md) | Set up a local development server |
| [Plugin structure](docs/plugin-structure.md) | Organize plugin files and namespaces |
| [FormAPI guide](docs/form-api-guide.md) | Build native Bedrock forms |
| [Dependencies guide](docs/dependencies-guide.md) | Use hard, optional, and bundled dependencies |
| [Manifest guide](docs/manifest-guide.md) | Configure Bedrock addon manifests |
| [MOTD colors](docs/motd-colors.md) | Color and formatting code reference |
| [UUID guide](docs/uuid-guide.md) | UUID formats and generation modes |

## Project structure

```text
.
├── api/          # JSON API endpoints
├── assets/       # CSS, JavaScript, images, and sounds
├── config/       # Application configuration and routes
├── docs/         # Developer guides
├── includes/     # Shared PHP utilities
├── languages/    # English and Persian translations
├── pages/        # Application pages and partials
├── API.md
├── CONTRIBUTING.md
├── INSTALL.md
└── README.md
```

## Contributing

Contributions, bug reports, and feature suggestions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request

## License

This project is distributed under the MIT License. See [LICENCE](LICENCE) for details
