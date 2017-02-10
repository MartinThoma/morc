Martins OCR Data (short: MORC) is a collection of documents for
training / benchmarking OCR systems.

## Contents

* `morc-data`: jpg images
* `morc-data-meta.csv`: A comma seperated list of
    * path: The path to an image / scan
    * writer: Identifier for writers. "unknown" can contain multiple writers
    * handwritten: 0 for False, 1 for True, 2 for mixed data
    * cursive: 0 for False, 1 for True, 2 for mixed data (every cursive file is handwritten)
    * contains images: 0 for False, 1 for True
    * contains tables: 0 for False, 1 for True
    * languages: ISO 639-1 code (en for English, de for German, ...)
      If more than one language is used, separate them with `::` (e.g.: "de::en")
    * contains math: 0 for False, 1 for True