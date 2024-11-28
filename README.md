# OpenLayers Box Selection

This repository demonstrates how to implement a box selection tool using OpenLayers, a popular open-source JavaScript library for displaying maps and geospatial data.

## Overview

The Box Selection tool allows users to draw a box on the map to select features within a defined area. Once the box is drawn, the selected features can be identified, and their properties can be displayed.

### Key Features:
- Select map features using a draggable rectangle (box) on the map.
- Display the selected feature names dynamically in an info box.
- Supports adding/removing features to/from the selection as the box is moved or resized.

## Demo

You can explore live examples of OpenLayers functionality [here](https://openlayers.org/en/latest/examples).

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/mrinmoy32/OpenLayers-Box-Selection.git
```

### 2. Install dependencies

If you need to install dependencies, use npm:

```bash
npm install
```

### 3. Start the project

After installation, you need to run the start script:

```bash
npm start
```

### 4. Open the project

One the project successfully runs, visit `http://localhost:5173/`

## Usage

The Box Selection tool integrates seamlessly with your OpenLayers map. Here's an overview of the functionality:

- **Add/Remove selection**: As you draw or resize the selection box, the features within the box will be selected and displayed in the `infoBox`.
- **Displaying selected names**: The selected feature names are shown in a list format inside the `infoBox`. If no features are selected, the `infoBox` will display 'None'.

## Contributing

If you want to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request. 

### Steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes to the branch.
4. Push your branch to your forked repository.
5. Submit a pull request with a clear description of the changes.

## License

This project is licensed under the MIT License.

## Links

- [OpenLayers Examples](https://openlayers.org/en/latest/examples)
- [OpenLayers API Docs](https://openlayers.org/en/latest/apidoc/)

