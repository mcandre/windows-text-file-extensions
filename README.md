# windows-text-file-extensions - a comprehensive list of Windows-centric text file extensions

A repository of file extensions that can reasonably be assumed to be Windows-centric text files (that should probably use CRLF line endings).

# The List

[windows-text-file-extensions.txt](https://github.com/mcandre/windows-text-file-extensions/blob/master/conf/windows-text-file-extensions.txt)

# Format

* One file extension per line.
* Lowercase.
* Basename of extension (omit the dot `.`).

# Things that should NOT be in the list

* `txt`, `xml`, and other formats not specific to Windows or other Microsoft systems should be omitted.
* `exe`, `msi`, and other binary formats should be omitted.

# Purpose

Q: Why would anyone want a list of Windows-centric text file formats?

A: To serve as a default list of files to ignore for certain kinds of static analysis.

Q: What?!

A: To make programs like [lili](https://github.com/mcandre/lili) behave better with Windows projects.
