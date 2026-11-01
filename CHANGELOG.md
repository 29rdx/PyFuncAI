# Changelog

## Unreleased

### Added

- `pyfuncai --version` prints the installed package version.
- `pyfuncai cache list --json` outputs an ordered array of cache keys, function
  names, modes, and creation timestamps. Empty caches produce `[]`; prompts,
  generated source, and provider configuration are omitted.
