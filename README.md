# Zork source code, 1978 January
This repository contains the source code for a January 1978 version of [Zork](https://en.wikipedia.org/wiki/Zork), an interactive fiction game created at MIT by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [zork](../main/zork)
The files within this directory are the Zork specific files from the ```9005201.tap``` tape image file within the ```/tots/recovered/vol2``` directory of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

The files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, ```LCF; ACT1 71```, for example. All files have been placed into this artificial zork directory for organizational purposes.

The [```ar1.random```](../main/zork/```ar1.random```) directory contains the extracted files from the ```ar1.random``` file within the [```taa```](../main/zork/taa) directory. The [```dungon.11```](../main/zork/ar1.random/dungon.11) and [```zork.3```](../main/zork/ar1.random/zork.3) files are the source code to the [```ts.zork```](../main/zork/sys2/ts.zork) file. The files were extracted recently and added to this directory by DDC digital archivist, Joe Carrano, for researcher ease of access.

The [```lcf```](../main/zork/lcf) and [```madman```](../main/zork/madman) directories contain the source code for the game.

The [```sys2```](../main/zork/sys2) directory contains the program used to start the game, ```ts.zork```.

The [```taa```](../main/zork/taa) directory contains multiple copies of an ```ar1.random``` file, which is an ITS archive file (similar to a ZIP file). The extracted files can be found in the [```ar1.random```](../main/zork/ar1.random) directory.

The files outside of these subdirectories, such as [```act1.71```](../main/zork/act1.71), etc., are the decrypted versions of files found in the [```lcf```](../main/zork/lcf) directory. The decrypted versions were created recently and added to this directory by DDC digital archivist, Joe Carrano, for researcher ease of access.  

Files with extensions ```.nbin``` and ```.save``` are binary compiled files.

There was a ```zork.log``` file within the [```madman```](../main/zork/madman) directory that detailed who played Zork at the time of creation. DDC excluded this file from public release to protect the privacy of those named.

### [codemeta.json](../main/codemeta.json)
This file is metadata about the Zork files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [```zork```](../main/zork) directory showing the original file timestamps as extracted from the tape image.

## Preferred Citation
[filename], Zork source code, 1978 January, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:0e61db4f256f1042f7dde19b052f8d982fe53c62](https://archive.softwareheritage.org/swh:1:dir:0e61db4f256f1042f7dde19b052f8d982fe53c62/)
## Rights
The ownership status of these files is not entirely clear. To the extent that MIT holds rights in these files, we are happy to support their broad public use.  Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
