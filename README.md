# GitHub Codespaces IHP Template

This is an IHP template configured to run on GitHub Codespaces and [VSCode Devcontainers](https://code.visualstudio.com/docs/devcontainers/containers). 

## Getting Started

### For New Projects
1. Create a repository from this template.
2. Run it in Codespaces / Devcontainers.
3. Wait for the initial setup to complete. This will take a few minutes and will use two bash windows, one of which will close when it's done. The other should be a blank terminal when it's done.
4. Run `devenv up` to start the server.
5. Have fun with IHP! :)

### An existing IHP project
To add support to an existing IHP project, simply copy the [devcontainer configuration](.devcontainer/devcontainer.json) to your project, 
placing it in `.devcontainer/devcontainer.json`. Then follow the above instructions.

## Note
Sometimes GitHub updates Codespaces or their base container image, which may break this devcontainer configuration. Please check here regularly for 
updates and post an issue if you have problems running a Codespace / Devcontainer. To update, simply copy the new `devcontainer.json` 
to your project, and then rebuild the container or recreate your Codespace / Devcontainer entirely.

See also [ihp.digitallyinduced.com](https://ihp.digitallyinduced.com/)
