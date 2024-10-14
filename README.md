# G-code Blockly

This repository provides an interactive G-code Blockly demo, allowing users to visually create G-code commands using blocks. It leverages the Blockly library to enable users to drag and drop blocks to build G-code snippets, which can then be displayed or executed.

## Features

- **User-Friendly Interface**: Drag-and-drop blocks to create G-code commands easily.
- **Custom Blocks**: Includes blocks for G-code commands (G, M, T) and parameters (X, Y, Z, etc.).
- **Code Generation**: Automatically generates G-code based on user-created blocks.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Getting Started

1. **Open the Demo**:
   Open the [Demo]().

## Usage

- **Show G-code**: Click the "Show G-code" button to display the generated G-code from the blocks you've created.
- **Run G-code**: The "Run G-code" button currently logs a message to the console. You can implement functionality for executing the G-code as needed.

## Block Definitions

### G-code Command Block

- **Inputs**:
  - Command Type (G, M, T)
  - Numeric Value
  - Parameters (X, Y, Z, etc.)

### G-code Parameter Block

- **Inputs**:
  - Parameter Type (X, Y, Z, etc.)
  - Numeric Value

## Dependencies

This project requires the Blockly library. The scripts are included via CDN in the HTML file:

```html
<script src="https://unpkg.com/blockly/blockly_compressed.js"></script>
<script src="https://unpkg.com/blockly/javascript_compressed.js"></script>
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Acknowledgements
Blockly: A library for building visual programming editors. Visit [Blockly] for more information.
