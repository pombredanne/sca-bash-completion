SCA Bash Completion
===================

A Bash completion script for HPE Fortify Source Code Analyzer (SCA).

Current features
-------------------
- Completion for many well-known ```sourceanalyzer``` switches
- Completion for existing build IDs (typing ```sourceanalyzer -b <tab>``` will list created IDs)
- Completion for ```fortifyclient``` (keywords, switches, token types etc.,)
- Completion for ```FPRUtility```, ```fortifyupdate```, ```ReportGenerator``` and ```SCAState``` switches

Installation
-------------------
Copy (or symlink for easier updates) the ```sourceanalyzer.sh``` script to your bash-completion directory (typically called ```bash_completion.d```).

If you're lucky, you can run ```echo $BASH_COMPLETION_DIR``` in your terminal and it will print out the path to the folder where the file should be placed.

Unfortunately, not all configurations support this, so here are a few common locations:

- MacPorts: ```/opt/local/etc/bash_completion.d/```
- Homebrew: ```/usr/local/etc/bash_completion.d/```
- Debian, Ubuntu & Cygwin: ```/etc/bash_completion.d/```

Tips
-------------------
If you specify environment variables ```SSC_URL``` and ```SSC_USER``` they will be used to complete the values for ```-url``` and ```-user``` respectively.

License
-------------------
The MIT License (MIT)

Copyright (c) 2016 Josh Anderson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of       the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
