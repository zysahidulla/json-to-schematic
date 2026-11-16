# JSON to Schematic

Turn a [Wokwi](https://wokwi.com/) `diagram.json` into a readable schematic and netlist in your browser.

## Use it

Open [`index.html`](./index.html) in a modern browser. No installation, build step, or server is required.

Load a diagram by dragging in a `diagram.json` file, choosing a file, pasting JSON, or loading the example. The generated schematic and connected-pin netlist appear below the controls.

## Features

- Resolves breadboard connections into electrical nets.
- Draws schematic symbols and component designators.
- Exports the schematic as SVG and copies the netlist.
- Supports light, dark, and automatic themes.
- Runs entirely in the browser; it does not upload diagrams to a server.

## Publish with GitHub Pages

1. Add `index.html`, `README.md`, and `LICENSE` to the root of this repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.
5. After GitHub Pages finishes deploying, the site URL will appear on the Pages settings screen.

## License

This project is available under the [MIT License](./LICENSE).
