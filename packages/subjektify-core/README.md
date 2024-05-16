# subjektify-core

`subjektify-core` is the fundamental library of the Subjektify ecosystem, providing essential building blocks, code generation for popular languages, and utilities for developing decentralized applications (dApps) using Subjektify.

## Features
- **Core Utilities**: Provides core utilities and functions essential for building dApps.
- **Code Generation**: Includes code generators for popular languages such as Solidity and TypeScript, simplifying the process of creating smart contracts and related components.
- **Compilers**: Contains compilers for supported languages, ensuring seamless integration and deployment.
- **Modular Architecture**: Designed to be highly modular and extensible, allowing seamless integration with other Subjektify packages.
- **TypeScript Support**: Written in TypeScript for type safety and improved developer experience.
- **Integration Ready**: Easily integrates with other tools and libraries in the Subjektify ecosystem.

## Installation

> [!NOTE]
> `subjektify-core` is already included in `subjektify-toolbox`. You only need to follow the below if you want to install the stand-alone version of the package.

To install `subjektify-core`, use npm or yarn:

```
npm install --save @subjektifylabs/subjektify-core
```

or for yarn:

```
yarn add @subjektifylabs/subjektify-core
```

## Usage

Add `subjektify-core` in your Subjektify config:

```javascript
require("@subjektifylabs/subjektify-core");
```

or in TypeScript

```typescript
import "@subjektifylabs/subjektify-core";
```

### Code Generation

`subjektify-core` provides code generation capabilities for popular languages like Solidity and TypeScript. You can use these generators to automatically produce code from your Subjekt definitions.

```typescript
import { generateSolidity, generateTypeScript } from "@subjektifylabs/subjektify-core";

// Generate Solidity code
const solidityCode = generateSolidity(subjektDefinitions);

// Generate TypeScript code
const typeScriptCode = generateTypeScript(subjektDefinitions);
```

### Compilers

`subjektify-core` includes compilers for supported languages to help you compile your code seamlessly.

```typescript
import { compileSolidity, compileTypeScript } from "@subjektifylabs/subjektify-core";

// Compile Solidity code
const compiledSolidity = compileSolidity(solidityCode);

// Compile TypeScript code
const compiledTypeScript = compileTypeScript(typeScriptCode);
```

## Contributing

We welcome contributions from the community! If you'd like to contribute to `subjektify-core`, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Implement your changes and add tests if applicable.
4. Open a pull request with a detailed description of your changes.

## License

`subjektify-core` is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more information.

## Support

If you encounter any issues or have questions about `subjektify-core`, please open an issue on GitHub or reach out to our community for support.

Happy coding with Subjektify!