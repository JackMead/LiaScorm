# Readme

## Viewing in dev mode

Easiest solution:
* Open in VSCode
* Install the `LiaScript-Preview` extension
* Open command palette (ctrl/cmd + shift + p) and search LiaScript:
    * Select "Preview your course in live mode"
    * View at <http://localhost:8000/liascript/index.html?http://localhost:8000/SampleDoc.md#2>

## Compiling to SCORM

* Install the CLI with `npm install -g --verbose @liascript/exporter`
* Then can run: `liaex -i .\SampleDoc.md --format scorm2004 --output out`
  * This format hasn't yet been tested