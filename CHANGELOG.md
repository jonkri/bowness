## Releases

## v1.1.0 (2023-05-10)
#### New features
  - The bowness binary now has a -v/--version commnand line flag (#4)
  - The reverse proxy can now be configured to use an API key (#5)

## v1.0.0 (2023-02-22)
  - Normalization of entity IDs was removed.
    Normalized IDs shouldn't be used anyway, and by removing this a
    dependency with a security alert could be removed.
  - Updated dependencies due to security alerts (GitHub dependabot).
    It doesn't seem like the security alerts were relevant for Bowness.
