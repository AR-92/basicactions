# basicactions

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of basic automation actions for workflow systems like n8n, Make, or Zapier.

## Description

`basicactions` is a repository containing fundamental automation building blocks designed for use in workflow automation systems. These actions provide essential functionality that can be composed together to create more complex automation workflows. Each action is designed to be simple, reliable, and reusable across different automation platforms.

## Key Features

- Collection of reusable automation actions
- Easy integration with popular workflow platforms (n8n, Make, Zapier)
- Well-documented and tested components
- Modular design for maximum flexibility
- Lightweight and efficient implementation
- Ready-to-use templates for common automation tasks

## Technologies Used

- JavaScript/Node.js
- JSON for configuration
- Standard web protocols (HTTP/HTTPS)
- Automation platform APIs (n8n, Make, Zapier)

## Installation

Since these are automation actions, installation depends on your automation platform:

### For n8n:
1. Download the action files from this repository
2. Import them into your n8n instance as custom nodes
3. Configure the required parameters

### For Make:
1. Download the action files
2. Import them as custom modules in your Make scenarios
3. Set up the necessary connections and parameters

### For Zapier:
1. Clone this repository
2. Follow Zapier's guidelines for creating custom integrations
3. Use the action templates as a starting point

## Usage

Each action is contained in its own directory with:
- An implementation file
- Documentation explaining usage
- Example configurations
- Test cases

To use an action:
1. Identify the action that matches your needs
2. Review the documentation and examples
3. Adapt the configuration to your specific use case
4. Test the action in your automation environment

## Project Structure

```
basicactions/
├── actions/              # Individual action directories
│   ├── send-email/       # Email sending action
│   ├── format-data/      # Data formatting action
│   ├── validate-input/   # Input validation action
│   └── ...               # Additional actions
├── templates/            # Template files for different platforms
│   ├── n8n/              # n8n-specific templates
│   ├── make/             # Make-specific templates
│   └── zapier/           # Zapier-specific templates
├── docs/                 # Documentation for each action
├── tests/                # Test cases for actions
├── examples/             # Example workflows using actions
└── README.md             # This file
```

## Available Actions

### send-email
Sends emails with customizable templates and attachments.

### format-data
Transforms and formats data between different formats (JSON, CSV, XML).

### validate-input
Validates input data against predefined rules and schemas.

### http-request
Makes HTTP requests with customizable headers, methods, and payloads.

### file-operation
Performs file operations (read, write, move, copy) in cloud storage.

### date-time
Handles date and time operations, formatting, and calculations.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- GitHub: [AR-92](https://github.com/AR-92)