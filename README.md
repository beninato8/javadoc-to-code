# javadoc-to-code

## Takes javadocs (.html) files and creates method headers with javadoc comments

 - None of the tools I found online seemed to work for this task, so I wrote my own
 - The code probably has many issues (besides (a lack) of style)
 - I wrote this in a few hours and have not done any extensive testing. It is very likely to not work on other javadocs.

## Installation

 - `$ git clone https://github.com/beninato8/javadoc-to-code`
 - Tested with Python 3.7.3
 - I used `bs4==0.0.1` to parse the html
  - To install: `python3 -m pip install bs4==0.0.1`

## Running

 - Put javadoc (.html) files in jdoc_in folder
 - `$ python3 javadoc_to_code.py`
 - Java (.java) files should be in jdoc_out folder