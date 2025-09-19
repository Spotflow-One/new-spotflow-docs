# Spotflow Documentation

<p align="center">
  <img src="./images/cover-images/read-cover.png" alt="Spotflow documentation cover image"/>
</p>

<div align="center">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-GPLv3-blue.svg" alt="License: GPLv3" />
  </a>
  <a href="https://docs.spotflow.one">
    <img src="https://img.shields.io/badge/docs-live-brightgreen.svg" alt="Live Documentation" />
  </a>
  <a href="https://slack.gg/bYqAp">
    <img src="https://img.shields.io/discord/1305511580854779984?label=Join%20Discord&logo=dis" alt="Join Slack Community" />
  </a>
</div>

## 🚀 Overview

Welcome to the official documentation repository for [Spotflow](https://spotflow.one), a comprehensive Merchant of Record solution for global merchants and businesses looking to expand. This documentation is built with [Mintlify](https://mintlify.com) and covers everything from quick start guides to detailed API references.

## 📚 Documentation Site

Visit our live documentation at [docs.spotflow.one](https://docs.spotflow.one)

## 🏗️ Documentation Structure

Our documentation is organized into five main sections:

### 1. **Setup & Features** 
- Getting started guides
- Platform features (subscriptions, one-time payments, disbursements, etc.)
- Business verification 

### 2. **Developer Resources**
- Integration guides and tutorials
- SDKs and mobile integration
- Testing tools

### 3. **API Reference**
- Complete API documentation
- Endpoint references for all resources
- Error codes and troubleshooting
- Code examples and best practices

### 4. **Changelog**
- Version history
- Feature updates
- Breaking changes
- Migration guides

## 🛠️ Development Setup

### Prerequisites

- Node.js 18.x or higher
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/spotflow-one/spotflow.git
   cd spotflow-docs
   ```

2. **Install the Mintlify CLI**
   ```bash
   npm i -g mintlify
   # or
   yarn global add mintlify
   ```

3. **Run the development server**
   ```bash
   mintlify dev
   ```

   The documentation will be available at `http://localhost:3000`

### Configuration

The documentation is configured through `docs.json` which includes:
- Navigation structure
- Theme customization
- SEO settings
- Integration configurations
- Redirect rules

## 📝 Contributing

Want to help improve our docs? Read our [contribution guidelines](./CONTRIBUTING.md) for details on how to get started.

- Fix typos, clarify explanations, or add examples
- Create new guides or update API docs
- Help with translations

All docs use MDX with frontmatter. Test changes locally with `mintlify dev` before submitting a pull request.

## 💙 Contributors

A heartfelt thank you to all our contributors for their valuable contributions and ongoing support!

<a href="https://github.com/spotflow/spotflow-docs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spotflow/spotflow-docs" />
</a>

## 🔧 Troubleshooting

### Common Issues

**Mintlify dev isn't running**
- Run `mintlify install` to reinstall dependencies
- Ensure you're in the directory containing `docs.json`

**Page loads as 404**
- Check that your file is included in the navigation structure in `docs.json`
- Verify the file path matches the navigation entry

**Images not displaying**
- Ensure images are in the `/images` directory
- Use absolute paths starting with `/images/`

## 🚀 Deployment

Documentation is automatically deployed when changes are pushed to the main branch. The deployment process:

1. Push changes to the `main` branch
2. GitHub Actions trigger the build process
3. Mintlify deploys the updated documentation
4. Changes are live at [docs.spotflow.one](https://docs.spotflow.one)

## 📄 License

This documentation is licensed under the GNU General Public License v3.0 (GPL-3.0). See the [LICENSE](LICENSE) file for details.

## 🤝 Support

- **Documentation Issues**: Open an issue in this repository
- **Community**: Join our [Slack community](https://slack.gg/bYqAp4ayYh)


## 🔗 Useful Links

- [Spotflow Merchant Portal](https://app.spotflow.co)
- [API Reference](https://docs.spotflow.one/api-reference/introduction)
- [Changelog](https://docs.spotflow.one/changelog/introduction)

---

<div align="center">
  Made with ❤️ by the Spotflow team
</div>