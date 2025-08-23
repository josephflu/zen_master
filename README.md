# Zen Master

**Feature Testing Suite for Kizen**

Zen Master (formerly KizenTester) is a testing utility for Kizen's REST API features, enabling QA teams and developers to validate AI functionality before front-end availability. It provides an intuitive web interface for testing multiple environments and managing API connections.

## Quick Install

```bash
curl -sSL https://github.com/josephflu/zen_master/releases/download/setup/zen_setup.sh | bash
```

This one-line installer will:
- Check for the `uv` package manager (and guide you to install it if needed)
- Download the latest version
- Create a Python virtual environment
- Install all dependencies
- Set up the `zenmaster` command

## Features

- **Multi-Environment Support**: Test against INTEGRATION, STAGING, PRODUCTION, and LOCAL environments
- **AI Chat Testing**: Interactive chat sessions with streaming responses
- **Knowledge Management**: Upload and manage knowledge base files
- **Auto-Updates**: Automatically checks for new versions on startup
- **Secure**: All credentials stored locally

## Usage

After installation, start Zen Master:

```bash
# From installation directory
./run.sh

# Or use the global command (after reloading shell)
zenmaster
```

The application will start on **http://localhost:8504**

### Getting Started

1. Navigate to **Settings** and add your Kizen API credentials
2. Select your target environment (Integration, Staging, Production)
3. Start testing using the Chat Tester, API Test, or other tools

## Updating

Zen Master automatically checks for updates on startup. When a new version is available, you'll see a notification.

To update manually:

```bash
./update.sh
```

## System Requirements

- **macOS** or **Linux**
- **Web browser** for the Streamlit interface

## Configuration

All configuration files are stored in the `config/` directory and are preserved during updates:
- API credentials
- Business configurations
- User preferences

## Support

For issues or questions, please open an issue on [GitHub](https://github.com/josephflu/zen_master/issues).

## License

MIT
