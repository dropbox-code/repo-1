# selproj

A tool to select an empty project's suffix from a list of projects using a prefix.

## Usage

```bash
go run main.go
```

The tool requires the following environment variables to be set:

- `AIVEN_TOKEN` - Aiven authentication token
- `AIVEN_PROJECT_NAME_PREFIX` - A prefix to filter projects by

## Example

```text
$ AIVEN_TOKEN=... AIVEN_PROJECT_NAME_PREFIX=test go run -tags tools .
test-project-2
```

## Development

There are no dependencies besides Go itself.

## Testing

Run the following command in the root of the repository to run the tests:

```bash
task test-selproj
```
