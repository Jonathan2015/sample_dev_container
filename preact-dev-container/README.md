# preact-dev-container

## CLI Commands

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# test the production build locally
npm run serve

# run tests with jest and enzyme
npm run test
```

For detailed explanation on how things work, checkout the [CLI Readme](https://github.com/developit/preact-cli/blob/master/README.md).

# Setup Dev Container

Available containers
* https://hub.docker.com/_/microsoft-vscode-devcontainers
* https://code.visualstudio.com/docs/devcontainers/create-dev-container

create devocontainer.json

```
// For format details, see https://aka.ms/devcontainer.json. For config options, see the
// README at: https://github.com/devcontainers/templates/tree/main/src/javascript-node
{
	"name": "Node.js",
	"image": "mcr.microsoft.com/devcontainers/javascript-node:16-bullseye",

	// Features to add to the dev container. More info: https://containers.dev/features.
	// "features": {},

	// Use 'forwardPorts' to make a list of ports inside the container available locally.
	"forwardPorts": [8080],

	// Use 'postCreateCommand' to run commands after the container is created.
	"postCreateCommand": "npm run dev"

	// Configure tool-specific properties.
	// "customizations": {},

	// Uncomment to connect as root instead. More info: https://aka.ms/dev-containers-non-root.
	// "remoteUser": "root"
}
```

Anzeige -> Befehlspalette => DevContainers:Reopen in Container
