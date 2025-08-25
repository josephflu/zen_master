# ZenKit

**The Essential Kizen API Testing Toolkit**

A powerful testing utility for Kizen's REST API, enabling QA teams and developers to validate AI features before front-end availability.

## Features

- 🤖 **AI Chat Testing** - Test chat functionality with multiple AI models
- 🔍 **Knowledge Base Search** - Query and validate knowledge base responses
- 🔌 **REST API Testing** - Direct endpoint testing with full request/response visibility
- 🏢 **Multi-Environment Support** - Switch between Integration, Staging, and Production
- 🔐 **Secure Configuration** - Local storage of API credentials
- 🎛️ **Interactive CLI** - Manage everything from a beautiful command-line interface

## Installation

### macOS/Linux

```bash
# Download and run the installer
curl -sSL https://github.com/josephflu/zen_master/releases/download/setup/zen_setup.sh | bash
```

The installer will:
- Download the latest version
- Set up Python environment
- Install all dependencies
- Create a `zen` command for easy access

## Usage

### Start ZenKit

After installation, you have two options:

```bash
# Option 1: Use the zen command (recommended)
zen

# Option 2: Navigate to installation and run
cd ~/zenkit
./run.sh
```

This opens the ZenKit CLI interactive menu where you can:
- Start/stop the web interface
- Check for updates
- View status
- Configure settings

### Web Interface

Once started, access the web interface at: **http://localhost:8504**

## CLI Commands

The CLI provides full control over ZenKit:


## Configuration

On first run, configure your API credentials through the Settings page in the web interface:

1. Start ZenKit (`zen` → Start ZenKit)
2. Navigate to Settings in the web interface
3. Add your business configuration
4. Select environment (Integration/Staging/Production)
5. Enter API credentials

Your configuration is stored locally and never transmitted.

## Updating

To check for and install updates:

1. Open the CLI: `zen`
2. Select "Check for Updates"
3. Follow the prompts to update if a new version is available

Updates preserve all your configurations and settings.

## Requirements

- macOS or Linux
- API credentials for your Kizen environment


## License

Proprietary - For authorized Kizen users only

---

*ZenKit is an internal tool for Kizen API testing and validation.*
