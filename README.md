# File Encryptor
 Encrypt (and decrypt) multiple files (and directories) at once

Uses AES 256 bit encryption with a secure random 32 bit salt.

Usage:

python encrypt.py file1 [file2] [file3] [dir1] [dir2] ...

Performance is more dependant on the number of files than the size of data being operated on.
