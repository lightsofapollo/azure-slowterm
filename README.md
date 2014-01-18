# azure-slowterm

Round-trip terminal results to azure and back (from stdin to stdout)
mostly for testing.

Both `AZURE_STORAGE_ACCESS_KEY` and `AZURE_STORAGE_ACCOUNT` environment variables must be set for this to work.


## Example:

```sh
# from the root of this repo
cat README.md | ./bin/azure-slowterm
```

## Usage

```sh
# run
azure-slowterm --help
```

## Notes:

This is obviously not the most efficient way to view content from stdout it is mostly here to test the responsiveness of the taskcluster live logging tools.

