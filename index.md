---
layout: "default"
title: "Dapodik CLI: Command-Line Tool for Indonesian Education Data 📊🇮🇩"
description: "Fast CLI tool for scraping Indonesian education data from DAPODIK. Fetch clean CSV/JSON for analysis and automation. 🌍📊"
---
# Dapodik CLI: Command-Line Tool for Indonesian Education Data 📊🇮🇩

![GitHub release](https://img.shields.io/github/release/creatopid/dapodik-cli.svg)
[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen)](https://github.com/creatopid/dapodik-cli/releases)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Formats](#data-formats)
- [Supported Regions](#supported-regions)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

Dapodik CLI is a command-line tool designed to fetch and export Indonesian education data. It utilizes data from Dapodik and Kemdikbud as references. This tool is not affiliated with Kemdikbud and is intended for educational and research purposes.

## Features

- Fetch and export data in CSV and JSON formats.
- Multi-level region support for detailed data retrieval.
- School-level details for in-depth analysis.
- Simple command-line interface for ease of use.
- Open-source and community-driven.

## Installation

To install Dapodik CLI, you need to have Node.js installed on your machine. Follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/creatopid/dapodik-cli.git
   ```

2. Navigate to the directory:

   ```bash
   cd dapodik-cli
   ```

3. Install the required packages:

   ```bash
   npm install
   ```

4. Run the tool:

   ```bash
   node index.js
   ```

For the latest version, [download the latest release here](https://github.com/creatopid/dapodik-cli/releases) and execute the necessary files.

## Usage

Dapodik CLI provides a straightforward command-line interface. Here’s how to use it:

### Basic Command

To fetch data, use the following command:

```bash
node index.js --region [region_code] --output [output_format]
```

Replace `[region_code]` with the code for the desired region and `[output_format]` with either `csv` or `json`.

### Example

To fetch data for Jakarta in CSV format, run:

```bash
node index.js --region DKI --output csv
```

### Options

- `--region`: Specify the region code (e.g., DKI for Jakarta).
- `--output`: Choose the output format (csv or json).
- `--help`: Display help information.

## Data Formats

Dapodik CLI supports two primary data formats:

### CSV

The CSV format is ideal for spreadsheet applications. It allows users to easily manipulate and analyze data.

### JSON

JSON format is useful for developers and applications that require structured data. It can be easily parsed and integrated into various systems.

## Supported Regions

Dapodik CLI supports multiple regions across Indonesia. Here are a few examples:

- DKI Jakarta
- Jawa Barat
- Jawa Tengah
- Jawa Timur
- Bali
- Sumatera Utara
- Sulawesi Selatan

You can find the complete list of region codes in the documentation.

## Contributing

Contributions are welcome! If you would like to contribute to Dapodik CLI, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.

Your contributions help improve the tool and benefit the community.

## License

Dapodik CLI is open-source software licensed under the MIT License. Feel free to use, modify, and distribute it.

## Contact

For any questions or feedback, please reach out via the issues section of the repository or contact me directly at [your-email@example.com].

For the latest version, [download the latest release here](https://github.com/creatopid/dapodik-cli/releases) and execute the necessary files.

![Education Data](https://example.com/path/to/image.jpg)

---

Thank you for your interest in Dapodik CLI. We hope this tool helps you in your educational and research endeavors.