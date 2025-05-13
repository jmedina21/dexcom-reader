# Dexcom Reader

A Raycast extension that allows you to view your Dexcom glucose readings directly from Raycast. This extension provides a convenient way to monitor your blood glucose levels without having to open the Dexcom app on your phone.

## Features

- View your current glucose readings
- Authenticate with your Dexcom account
- Quick access to your glucose data through Raycast

## Installation

1. Install the extension from the Raycast Store
2. Run the "Authenticate with Dexcom" command
3. Enter your Dexcom account credentials
4. Start using the "Glucose" command to view your readings

## Commands

- `Glucose`: View your current glucose readings from Dexcom
- `Authenticate with Dexcom`: Set up your Dexcom account credentials

## Development

This extension is built with:

- TypeScript
- React
- Raycast API
- Axios for API requests

### Prerequisites

- Node.js
- Raycast
- A Dexcom account

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Building

To build the extension:

```bash
npm run build
```

## ISSUES

- I haven't properly tested the links to get the info if your account was created outside of North America, so feel free to open an issue or a PR if you encounter this

## Author

- Pablo Medina
