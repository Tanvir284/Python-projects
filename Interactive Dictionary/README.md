# Interactive Dictionary

This project provides a simple console-based dictionary search tool written in Python.

## Purpose
- Look up English terms quickly from a local JSON file.
- Suggest close matches when a term is misspelled.

## Data Source
- The dictionary data lives in `076 data.json` which contains an object mapping each word to a list of definitions.
- Example entry:
  ```json
  {
    "abandoned industrial site": [
      "Site that cannot be used for any purpose, being contaminated by pollutants."
    ]
  }
  ```
- The scripts expect a file named `data.json`. Rename or copy `076 data.json` to `data.json` in the same folder before running them.

## Running the Console Scripts
1. Open a terminal and switch to the directory:
   ```bash
   cd "Interactive Dictionary"
   cp '076 data.json' data.json   # one-time setup
   ```
2. Run either of the scripts:
   ```bash
   python Console_Dictionary.py
   # or
   python Console_dictionary2.py
   ```
3. Enter a word when prompted and view the definitions or suggestions.

## Possible Enhancements
- Build a graphical interface for easier use.
- Expose the dictionary as a REST API so it can be queried programmatically.
- Add advanced search features such as partial matches or synonyms.
