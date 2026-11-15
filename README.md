# CatalystUI Implementations

The directory of projects and libraries in the CatalystUI ecosystem, hosted at [catalystui.org/implementations](https://www.catalystui.org/implementations/).

This repository contains the Implementations landing page, ecosystem index, and top-level navigation. Individual libraries maintain their own documentation in a `docs/` folder in their respective repositories.

## Structure

- `md/manifest.json` defines the sidebar.
- `md/lang/en-US/` contains the default-language directory pages.
- The Ecosystem navigation groups implementations by programming language.

To add a library, list it under the appropriate language in the manifest and ecosystem pages, and configure its documentation source in the website repository. Temporary directory entries at library routes are replaced by the library's own documentation when its source becomes available.

## License

The source and documentation in this repository are licensed under the [Apache License 2.0](LICENSE).
