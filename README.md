# LTFS Build docker action for Ubuntu 19.10 (Eoan)

This action builds the LTFS package on Ubuntu 19.10

## Inputs

### `destination`

**Required** Destination of install。 Default is `/tmp/ltfs`。

## Outputs

None

## Usage

```
uses: LinearTapeFileSystem/Ubuntu1910-Build@v1.0
with:
  destination: '/tmp/ltfs'
```
