# FormatFixer
Python script to fix the formatting of various files in your project.

* Place the `format-fixer.py` and `config-formatting.txt` in the root directory of your project.
* Update `config-formatting.txt` to include all the file patterns to modify and with what style.
* Run the script using Python 3. No args.

You can ignore files and directories using `IGNORE` and `BAD_PATH` meta-styles respectively to exclude specific suffixes.

The following styles are supported. Please make pull requests to add more!

| Name | ID for config file | Tab Behavior | Newlines  | Encoding | blank line at end | use BOM | other |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Acrylic | ACRYLIC | 4 spaces | \n | UTF8 | Yes | No | | 
| C# | CSHARP | 4 spaces | \r\n | UTF8 | Yes | Yes | |
| C# Project | CSPROJ | 2 spaces | \r\n | UTF8 | No | Yes | Set `ToolsVersion=14.0` |
| Crayon | CRAYON | 4 spaces | \n | UTF8 | Yes | Yes | |
| Java | JAVA | 4 spaces | \n | UTF8 | Yes | No | |
| Java Android | JAVA_ANDROID | 2 spaces | \n | UTF8 | Yes | Yes | |
| JavaScript | JAVASCRIPT | 1 tab | \n | UTF8 | Yes | Yes | |
| JSON | JSON | 4 spaces | \n | UTF8 | Yes | No | |
| MarkDown | MARKDOWN | 2 spaces | \n | UTF8 | Yes | No | |
| Pastel | PASTEL | 4 spaces | \n | UTF8 | Yes | Yes | |
| PHP | PHP | 4 spaces | \n | UTF8 | No | No | |
| Python | PYTHON | 2 spaces | \n | UTF8 | Yes | No | |
| Python | PYTHON_4_SPACES | 4 spaces | \n | UTF8 | Yes | No | |
| Swift | SWIFT | 4 spaces | \n | UTF8 | Yes | No | |
| XCode Project | PBXPROJ | 1 tab | \n | UTF8 | Yes | No | Resets the Developer Team ID field |
