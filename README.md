<!-- prettier-ignore-start -->
<div align="center">
  <h1>Dicom Web Viewer</h1>
  <p><strong>Dicom Web Viewer</strong> is a customized web application for viewing medical images (DICOM).
  It is built on top of the open-source <a href="https://ohif.org/">OHIF Viewer</a>, with UI/UX improvements and workflow-specific enhancements.</p>
</div>

<div align="center">
  <a href="https://dicom-web-viewer-demo.vercel.app/"><strong>Live Demo</strong></a> |
  <a href="https://github.com/riccardosapuppo/dicom-web-viewer"><strong>Source Code</strong></a>
</div>

<hr />
<!-- prettier-ignore-end -->

## About

**Dicom Web Viewer** allows you to load, explore, and analyze DICOM data from any [DICOMweb](https://www.dicomstandard.org/using/dicomweb/) compatible source.
It comes with a ready-to-use set of tools for navigation, annotations, and measurements, plus advanced 2D and 3D visualization modes.

Based on OHIF, the project is highly **configurable** and **extensible**: you can add custom extensions, modify the toolbar, integrate authentication systems, and more.

## Features

- DICOM medical image viewing
- 2D & 3D support (MPR, Volume Rendering, MIP)
- Interactive annotations and measurements
- Customizable toolbar with additional tools (e.g., Flip Vertical, Rotate Left)
- DICOMweb archive compatibility
- Localization and hotkey support
- Offline mode

## Why Choose Dicom Web Viewer

- **Open Source & Extensible** → create custom extensions or tools without maintaining a fork
- **Improved User Experience** → a cleaner interface optimized for faster workflows
- **Standards-based** → powered by OHIF’s robust foundation and active community

## Getting Started

### Requirements
- [Yarn 1.20.0+](https://yarnpkg.com/en/docs/install)
- [Node 18+](https://nodejs.org/en/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/riccardosapuppo/dicom-web-viewer.git
   cd dicom-web-viewer

2. Install dependencies:
   ```bash
   yarn install

3. Start in development mode:
   ```bash
   yarn run dev

## Acknowledgments

This project is built on [OHIF Viewer](https://ohif.org/), an open-source framework by the Open Health Imaging Foundation.
Special thanks to the OHIF community for providing the foundation on which this project was developed.

## License

MIT © [Riccardo Sapuppo](https://github.com/riccardosapuppo)
