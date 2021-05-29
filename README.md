# RefFormer
Simple script to sort references in document
## How to use
1. Install [git](https://git-scm.com/downloads)
3. Install [python](https://www.python.org/downloads/)
5. Install [pip](https://pip.pypa.io/en/stable/installing/)
7. Run `pip install python-docx`
8. Run `git clone https://github.com/1101AlexZab1011/RefFormer.git`
9. Save the document in ".docx" format
10. Edit ref-former-script.py, line 139: specify path to your document
11. **Make backup of your document before run! RefFormer will edit the given file! I do not take responsibility for what happens to your file!**
12. **Mark your references section by words "References section" in the separate line before**
13. Run `python /path/to/ref-former-script.py`
14. Enjoy
## What the script can do
* Sort all references in increasing order
* Correctly recognize multireferences like `[1, 2]`
* Correctly recognize repeating references
* Stop working if unused references are found
## What the script **can not** do
* Work with ".doc" format
* **Recognize references in lists and tables**
* Work with unused references
* recognize more than 8 references in a row. Example: `[1, 2, 3, 4, 5, 6, 7, 8, 9]`

> *I have not tested this script on Windows, so I don’t know how it will work on it.*
