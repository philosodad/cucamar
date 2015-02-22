= Plan of Attack

1. Create an executable that will search in the current folder for a "features" folder.
* executable is called cucamar
* installs to usr/local?
* outputs correct error message if folder not found
2. Have that executable scan the features folder for *.features files and parse them.
* output error messages for syntax errors
* parses gherkin -- into ast?
3. Search the `features/steps` folder for .ex files with step definitions.
* outputs correct errors if no `steps` folder
* prints step definitions to stdout if missing
* matches all the things? (examples/all the regex/etc?)
5. Find existing steps and run them in the correct order.

Should this be approached iteratively? Parse a small subset of gherkin all the way through, also step definitions?
