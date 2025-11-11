# RexLit Test Data

This repository contains sample documents and test data for RexLit, an offline-first e-discovery toolkit.

## Purpose

This repository is maintained as a separate git submodule to keep the main RexLit codebase lean while providing comprehensive test data for development and testing.

## Contents

- **EDRM specific data**: Sample documents from EDRM (Electronic Discovery Reference Model) test sets
- **Public websites data**: Various document types from public sources for testing different file formats

## Usage

This repository is typically used as a git submodule in the main RexLit repository:

```bash
# In the main RexLit repository
git submodule update --init --recursive
```

The test data will be available at `rexlit/docs/sample-docs/` in the main repository.

## Size

This repository contains approximately 168MB of test data including:
- RTF documents (~13MB)
- DOC files
- CSV files
- Images (JPG)
- Email archives (mbox)
- Various other document formats

## License

Test data files are provided for testing and development purposes only.

