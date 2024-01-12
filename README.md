# mevitco.ProFile.Client

## Description

Command-line client for the [mevitco.ProFile](https://profile.mevitco.de) service.
Allows you to efficiently download VERY LARGE files from a ProFile session.

## Usage

``` 
===================================================
   Mevitco ProFile Console (Preview)
===================================================

USAGE:
    mevitco.ProFile.Client.exe [session] [OPTIONS]

ARGUMENTS:
    [session]    Url to download from, e.g. https://profile.mevitco.de/download/{sessionid}

OPTIONS:
                     DEFAULT
    -h, --help                    Prints help information
    -v, --version                 Prints version information
    -f, --file                    ID of a single file to download
    -o, --output     downloads    Output directory to store the downloaded files
    -c, --command                 Command: 'download' or 'list'
    -b, --beep                    Beep when all files were downloaded
```