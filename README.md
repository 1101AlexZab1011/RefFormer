# RefFormer
Simple script to sort references in document
## How to use
1. Install [python](https://www.python.org/downloads/)
1. Install [pip](https://pip.pypa.io/en/stable/installing/)
1. Run `pip install python-docx`
1. Save the document in ".docx" format
1. Edit ref-former-script.py, line 139: specify path to your document
1. **Make backup of your document before run! RefFormer will edit the given file!**
1. Mark your references section by words "References section" in the separate line before
1. Run `python /path/to/ref-former-script.py`
1. Enjoy
## What the script can do
* Sort all references in increasing order
* Correctly recognize multireferences like `[1, 2]`
* Correctly recognize repeating references
* Stop working if unused references are found
## What the script **can not** do
* Work with ".doc" format
* **Recognize references in lists and tables**
* Work with unused references
* Work correctly if all references are already sorted **Do not run the script twice!**
