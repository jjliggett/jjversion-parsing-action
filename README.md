# jjversion-parsing-action

jjversion-parsing-action is a node12 JavaScript GitHub Action that parses the output of <https://github.com/jjliggett/jjversion>, providing several outputs for usage in GitHub workflows. This action is used by <https://github.com/jjliggett/jjversion-action>, which gets a version for the repository using the jjversion Go package and then parses the version JSON output using this action.

## Licensing

The version parsing code uses several dependencies which are compiled and distributed in the dist/index.js file. Licenses for the dependencies included can be found in the <https://github.com/jjliggett/jjversion-parsing-action/blob/root/dist/licenses.txt> file.

### VS Code Dev Container

VS Code Dev Containers is a development tool that utilizes a Docker container as a "full-featured development environment." Information regarding dev containers can be found at: <https://code.visualstudio.com/docs/remote/containers>.

This repository uses a dev container for development of the JavaScript action.

The dev container is a debian container with node using library scripts and a Dockerfile template from <https://github.com/microsoft/vscode-dev-containers> It also installs jq, build-essential, and @vercel/ncc within the container.

The following extensions are included as part of the dev container:

- eamodio.gitlens

License information for the dev container can be found at the following links:

- <https://github.com/microsoft/vscode-dev-containers/blob/main/LICENSE>
- <https://github.com/microsoft/vscode-dev-containers/blob/main/NOTICE.txt>
- <https://github.com/nodejs/node/blob/master/LICENSE>
- <https://metadata.ftp-master.debian.org/changelogs//main/b/build-essential/build-essential_12.9_copyright>
- <https://github.com/stedolan/jq/blob/master/COPYING>
- <https://github.com/vercel/ncc/blob/main/LICENSE>
- <https://github.com/Axosoft/vscode-gitlens/blob/main/LICENSE>
