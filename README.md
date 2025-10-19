# OTP Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight, zero-dependency TypeScript library for generating secure One-Time Passwords (OTPs).

## Features

- 🚀 Generate random numeric OTPs of custom length
- 🔒 Secure random number generation
- 📦 Zero dependencies
- 🛠 Written in TypeScript with full type definitions
- ⚡ Lightweight and fast

## Installation

```bash
npm install otpx-test
# or
yarn add otpx-test
# or
pnpm add otpx-test
```

## Usage

### Basic Usage

```typescript
import { generateRandomDigits } from "otpx-test";

// Generate a 4-digit OTP (default)
const otp = generateRandomDigits();
console.log(otp); // e.g., '1234'

// Generate a 6-digit OTP
const sixDigitOtp = generateRandomDigits(6);
console.log(sixDigitOtp); // e.g., '123456'
```

### Available Functions

#### `generateRandomDigits(length?: number): string`

Generates a random numeric OTP of the specified length.

- `length` (optional): The length of the OTP to generate. Defaults to 4.
- Returns: A string containing the generated OTP.

## Development

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Build the project:
   ```bash
   npm run build
   ```
4. For development with watch mode:
   ```bash
   npm run dev
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

👤 **Jay**

- GitHub: [@JaySyntax](https://github.com/JaySyntax)

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/JaySyntax/otp-generator/issues).

## Show your support

Give a ⭐️ if this project helped you!
