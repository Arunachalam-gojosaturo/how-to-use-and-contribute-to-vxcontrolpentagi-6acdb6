# I'm trying to run the vxcontrol/pentagi example application, but I'm getting errors due to missing dependencies.

_Install the required dependencies for the vxcontrol/pentagi example application using Go modules._

## Steps

1. First, navigate to the example application directory using `cd examples/myapp`.
2. Next, run the command `go mod download` to download the required dependencies.
3. Then, run `go build` to build the example application.
4. If you encounter any issues, try running `go mod tidy` to ensure your dependencies are up-to-date.
5. Finally, run the example application using `go run main.go`.

## Pitfalls

- Forgetting to run `go mod download` before building the example application, which can lead to missing dependencies