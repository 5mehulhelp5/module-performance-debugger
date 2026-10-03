# Changelog

All notable changes to this extension are documented here. The format
is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.1.2] - 2026-10-03

### Fixed
- The stored-run redaction step no longer empties the summary or query details of a run whose stored data cannot be decoded; such rows are left as they are.
- The redaction step keeps the parameter names of repeated-query bind values and masks only the sample values.
- Redacted page URLs keep their #fragment when the URL also has a query string.
