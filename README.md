# wrun

One-shot execution tool for remote scripts 

## Usage

Example:

```bash
wrun https://raw.githubusercontent.com/acme/demo/master/script.sh --verbose argument1
```

## How it works

`wrun` will download a copy of the given remote script to a temporary directory, execute it once, then remove the local copy.
