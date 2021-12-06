# LZ2TreeFile decompressor

This code can decompress a file in LZ2TreeFile format.  Use it like so:

    node index.js input.cd3 > output.txt

If node.js is not installed, download an executable from [releases](https://github.com/aratelle-hepeng/lz2treefile/releases) and use it like so:

    lz2treefile-win.exe input.cd3 > output.txt

It is also possible in most shells to redirect file input:

    node index.js < input.cd3 > output.txt

It really needs to be rewritten as a stream transformer, and a corresponding
compressor should be implemented so that files can be changed and recompressed.

## Licence

GPL3
