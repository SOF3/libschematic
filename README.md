libschematic
============

This is a virion for schematic file I/O.

The Schematic file format is compatible with the common one, except that libschematic adds the `POpaque` ByteArray bit stream to specify blocks that should replace existing blocks. The [SchematicFile class][SchematicFile] contains a specification of the format.

[SchematicFile]: src/sofe/libschematic/SchematicFile.php
