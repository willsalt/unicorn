# Unicorn
Libraries for PDF handling

This repository contains various libraries with PDF writing functionality, along with associated libraries for handling OpenType fonts and the PDF standard fonts.  This functionality may be somewhat limited and patchy, as its features have been determined solely by the needs of other projects, but it is a largely from-scratch pure-.NET implementation that does not rely on other PDF writing or parsing libraries.

## External dependencies

The only external dependency used for PDF reading and writing is [SharpZipLib](https://github.com/icsharpcode/SharpZipLib), used to compress PDF datastreams.

The command-line tools in the repository also use [CommandLineParser](https://github.com/commandlineparser/commandline) for option parsing.
