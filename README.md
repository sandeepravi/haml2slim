# Haml2Slim

[Haml](https://github.com/nex3/haml) to [Slim](https://github.com/stonean/slim) converter.

## Usage

You may convert files using the included executable `haml2slim`.

    # haml2slim -h

    Usage: haml2slim INPUT_FILENAME_OR_DIRECTORY [OUTPUT_FILENAME_OR_DIRECTORY] [options]
            --trace                      Show a full traceback on error
        -d, --delete                     Delete HAML files
        -h, --help                       Show this message
        -v, --version                    Print version

Alternatively, to convert files or strings on the fly in your application, you may do so by calling `Haml2Slim.convert!`.

## License

This project is released under the MIT license.

## Author

[Fred Wu](https://github.com/fredwu)
