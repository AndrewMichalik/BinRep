BinRep
======
Binary File Replacement Utility

Command line utility for replacing string (ASCII or Hex) within a file.

    Usage: bfr [-help] OldStr NewStr OldFile [NewFile] [-b -d]
       OldStr: Original string.
       NewStr: Replacement string (\"\" = none)
       OldFile: Source filename.
       NewFile: Target filename, if different from OldFile.
       -b : Backup file creation inhibited.
       -d : Date preserved from OldFile.
       Notes: Environment TMP= specifies temp work files directory.
              Use \\xx (xx = hex value) for special characters.
              "\" = \\5c, " " = \\20

This repository contains code and materials that Andrew Michalik had previously produced for his wholly owned corporation (Vector Information Systems, Inc) and for which he has retained copyrights.
