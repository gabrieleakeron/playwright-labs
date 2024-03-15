# playwright-labs
Un progetto per sperimentare playwright

# Install
npm i

# System Requirements
 - Node.js 18+
 - Windows 10+, Windows Server 2016+ or Windows Subsystem for Linux (WSL).
 - MacOS 12 Monterey, MacOS 13 Ventura, or MacOS 14 Sonoma.
 - Debian 11, Debian 12, Ubuntu 20.04 or Ubuntu 22.04, with x86-64 or arm64 architecture.

# Running tests
npm run test

# HTML Test Reports
npm run show-report 

# Running Tests in UI Mode
npm run test:ui

# Run tests in VS Code
## Extension
https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright

## Debug



# Updating Playwright
npm install -D @playwright/test@latest
npx playwright install --with-deps

## Check version 
npx playwright --version 