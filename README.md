# pyobfuscate

obuscate python source code 混淆 python 源代码的小工具

# Description
Origin resource is: https://github.com/astrand/pyobfuscate

This script based on pyobfuscate project. Increasing some awesome function such as support total dir conversion.

# Usage

```
python pyobfuscate.py -h

Usage:

pyobfuscate [options] <file>

Options:

-h, --help              Print this help.
-i, --indent <num>      Indentation to use. Default is 1.
-s, --seed <seed>       Seed to use for name randomization. Default is
                        system time.
-r, --removeblanks      Remove blank lines, instead of obfuscate
-k, --keepblanks        Keep blank lines, instead of obfuscate
-f, --firstcomment      Remove first block of comments as well
-a, --allpublic	        When __all__ is missing, assume everything is public.
                        The default is to assume nothing is public.
-v, --verbose	        Verbose mode.
```

# Example

## eg1: python pyobfuscate test.py

this command can produce a file handled after by the obfuscate handler.

Note!: this script can not handle Non-python file.

# Disclamer

This script is for education/research purposes only. The author takes NO responsibility ay for how you choose to use any of the tools provided
