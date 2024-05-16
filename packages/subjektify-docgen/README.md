# subjektify-docgen

subjektify-docgen is a powerful tool designed to generate comprehensive documentation for Subjektify projects. It simplifies the process of creating and maintaining up-to-date documentation for decentralized applications built with Subjektify.

## Features
- **Automatic Documentation Generation**: Generates detailed documentation from your Subjektify project configuration and source files.
- **Customizable Output**: Supports various output formats and customization options to fit your project's needs.
- **Integration with Build Tools**: Easily integrates with common build tools and CI/CD pipelines to automate documentation generation.

## Installation

> [!NOTE]
> `subjektify-docgen` is already included in `subjektify-toolbox`. You only need to follow the below if you want to install the stand-alone version of the package

To install subjektify-docgen, use npm or yarn:

```
npm install --save-dev @subjektifylabs/subjektify-docgen
```

or for yarn:

```
yarn add --dev @subjektifylabs/subjektify-docgen
```

## Usage

Add subjektify-docgen in your Subjektify config:

```
require("@subjektifylabs/subjektify-toolbox");
```

or in typescript

```
import "@subjektifylabs/subjektify-toolbox";
```

You can then run the `docgen` command to generate md files by default

```
npx subjektify docgen
```

## License

`subjektify-docgen` is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more information.

## Support

If you encounter any issues or have questions about `subjektify-docgen`, please open an issue on GitHub or reach out to our community for support.

Happy coding with Subjektify!