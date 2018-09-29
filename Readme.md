
# Export Annotations from PDFs

Initial source taken from: https://github.com/0xabu/pdfannots/

Changes:

* Use `docopt` for CLI

* Add support to print only the counts
    + So you can see which documents have any annotations
* Count Ink based annotations
    - Such as the ones generated using Apple Pencil!

* Disabled printing of Page numbers

## todo

* Don't group by annotation type

* Take input page number range
    - To make it faster?

* Streaming print

* Better use Markdown GFM Syntax
    - Highlight

    - Comment
        + `>` & line

    - Underline

## bugs

* Replace `` with `'`
* Replacements
    - `` & `` with `"`
