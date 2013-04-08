# World of Warcraft DBC Library

This library allows creation, reading and export of World of Warcraft's client-side database files.

These so-called DBCs store information required by the client to operate successfully and can be extracted from the MPQ archives of the actual game client.

**Required PHP version: 5.x**

Licensed under the **MIT** license, see LICENSE for more information.


## Getting Started

Check out the `examples` to get started.


## Usage Notes

* String localization will only provide accurate results when used with the US English (enUS) or British English (enGB) distributed DBCs.

* Attempting to read DBCs with a non-standard field size, **may fail**.
