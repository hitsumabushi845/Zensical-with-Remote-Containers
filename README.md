
# Zensical-with-Remote-Containers
This is a template repository to create [Zensical](https://zensical.org/) document with VSCode [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

## Requirements

- VSCode or VSCode based IDE like Cursor
- Dev Containers (as VSCode extension)
- Docker

## Usage

1. [Generate](https://github.com/hitsumabushi845/Zensical-with-Remote-Containers/generate) a new repository based on this template.
2. Clone it and open via VSCode
3. Open the project on Dev Containers
   `Cmd + Shift + P -> Dev Containers: Reopen in Container`
4. Open `Run` tab on left side-bar, then run `Launch Chrome against localhost`.
   - It executes `zensical serve` command and open `http://locahost:8000` via Google Chrome automatically.
5. You can enjoy real-time edit your Zensical document!
6. If you would like to terminate `zensical serve` and close the browser, you only need to do is clicking `stop` button.
