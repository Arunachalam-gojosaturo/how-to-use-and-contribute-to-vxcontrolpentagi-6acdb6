# I want to add a new feature to the vxcontrol/pentagi framework, but I'm not sure how to test it.

_Write unit tests for your new feature using Go's built-in testing package._

## Steps

1. First, create a new test file for your feature using `touch myfeature_test.go`.
2. Next, import the required testing packages using `import ( 'testing' )`.
3. Then, write test functions for your feature using the `func TestMyFeature(t *testing.T) { ... }` syntax.
4. Use the `t.Errorf` function to report any test failures.
5. Finally, run your tests using the command `go test -v`.

## Pitfalls

- Forgetting to use the `t.Errorf` function to report test failures, which can lead to silent test failures