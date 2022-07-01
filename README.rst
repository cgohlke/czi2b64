Convert Zeiss CZI to SimFCS B64 files
=====================================

Czi2b64 is a command line application written in C++ to convert
Carl Zeiss Image CZI files to SimFCS B64 binary files.

Usage: ``czi2b64.exe [--group] <file.czi> [<file.b64>]``

:Author: `Christoph Gohlke <https://www.cgohlke.com>`_
:Version: 2022.7.1

Revisions
---------

2022.7.1

- Update metadata.

2019.11.5

- Add option to convert Fast Airyscan using detector groups.

2018.6.17

- Convert Fast Airyscan CZI files.

2018.4.28

- Initial release for Airyscan FCS files.

Requirements
------------

- Microsoft Visual Studio 2019
- `LibCZI 501b133 <https://github.com/zeiss-microscopy/libCZI>`_
  (July 19, 2019).
