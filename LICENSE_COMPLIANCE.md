# License Compliance Documentation

## Third-Party Software Usage

This project uses the `blackbox_decode` tool from the cleanflight/blackbox-tools project for BBL file decoding functionality.

### cleanflight/blackbox-tools License Information

**Project**: cleanflight/blackbox-tools  
**Repository**: https://github.com/cleanflight/blackbox-tools  
**License**: GNU General Public License version 3 (GPLv3)  
**Status**: Archived (read-only as of April 19, 2023)

### License Compliance Requirements

The cleanflight/blackbox-tools project is licensed under GPLv3, which requires:

1. **Source Code Availability**: When distributing the binary, the source code must be made available
2. **License Notice**: The GPLv3 license text must be included
3. **Attribution**: Proper attribution to the original authors
4. **Copyleft**: Any derivative works must also be licensed under GPLv3

### Our Usage

We use the `blackbox_decode` binary tool as an external utility for parsing BBL files. This constitutes:
- **Tool Usage**: We execute the binary as a separate process
- **No Linking**: We do not link against the code or include it in our application
- **No Distribution**: We do not redistribute the blackbox_decode binary

### Compliance Actions Taken

1. **Attribution**: This document provides proper attribution to the cleanflight project
2. **License Reference**: Link to the original repository and license information
3. **Usage Documentation**: Clear documentation of how the tool is used
4. **Separate Installation**: Users must install blackbox_decode separately

### Installation Instructions for Users

To use this application, you must separately install the blackbox_decode tool:

1. Visit: https://github.com/cleanflight/blackbox-tools/releases
2. Download the appropriate binary for your operating system
3. Place the binary in your system PATH or specify its location in the application configuration

### Legal Notice

This project respects the GPLv3 license of cleanflight/blackbox-tools. The blackbox_decode tool is used as an external utility and is not distributed with this application. Users must obtain and install it separately according to the terms of the GPLv3 license.

For the full GPLv3 license text, see: https://www.gnu.org/licenses/gpl-3.0.html

### Additional Third-Party Licenses

The cleanflight/blackbox-tools project includes several third-party libraries:
- **libcairo**: LGPL
- **zlib**: MIT License  
- **libpng**: MIT License
- **Source Sans Pro font**: SIL Open Font License
- **IMU code from Baseflight**: GPLv3

These licenses apply to the blackbox-tools binary and do not affect this project directly.
