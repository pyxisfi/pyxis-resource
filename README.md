# Pyxis App Resources

This repository contains resources and assets for the Pyxis application.

## Overview

Pyxis is a comprehensive application that requires various resources for proper functionality and user experience. This repository serves as a centralized location for all static assets, tokens, and other resources used by the Pyxis application.

## Directory Structure

```
pyxis-resource/
├── tokens/                 # Token assets and icons
│   └── PXUSD.png          # PXUSD token icon
└── README.md              # This file
```

## Resources

### Tokens

The `tokens/` directory contains visual assets for various tokens used within the Pyxis ecosystem:

- **PXUSD**: The native stablecoin token of the Pyxis platform
  - File: `tokens/PXUSD.png`
  - Format: PNG
  - Usage: Displayed in the application interface for balance, transactions, and token selection

## Usage

These resources are intended to be used by the Pyxis application. When integrating these resources:

1. Ensure proper file paths are maintained when referencing assets
2. Follow the existing naming conventions for any new assets added
3. Maintain the directory structure to keep resources organized

## Contributing

When adding new resources to this repository:

1. Place assets in the appropriate directory (e.g., token icons in `tokens/`)
2. Follow the existing naming conventions
3. Use appropriate file formats (PNG for icons, SVG for scalable graphics when possible)
4. Optimize assets for web use to ensure fast loading times
5. Update this README to document any new resources added

## File Formats and Standards

- **Icons**: PNG format with transparent backgrounds, recommended size 128x128px or 256x256px
- **Images**: Optimize for web use while maintaining quality
- **Naming**: Use uppercase for token symbols (e.g., `PXUSD.png`)

## License

Please refer to the main Pyxis project repository for licensing information regarding these resources.

## Contact

For questions or issues related to these resources, please contact the Pyxis development team.