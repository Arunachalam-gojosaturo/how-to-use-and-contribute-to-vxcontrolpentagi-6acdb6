# I want to set up a new Go project using the vxcontrol/pentagi framework, but I'm not sure where to start.

_Initialize a new Go project with vxcontrol/pentagi using the provided CLI tool._

## Steps

1. First, install the vxcontrol/pentagi CLI tool by running the command `go install github.com/vxcontrol/pentagi/cmd/pentagi@latest` in your terminal.
2. Next, create a new directory for your project and navigate into it using `mkdir myproject && cd myproject`.
3. Then, run the command `pentagi init` to initialize a new vxcontrol/pentagi project.
4. This will create a basic directory structure and configuration files for your project.
5. Finally, run `go mod tidy` to ensure your project's dependencies are up-to-date.

## Pitfalls

- Forgetting to run `go mod tidy` after initializing the project, which can lead to dependency issues