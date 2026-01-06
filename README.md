# Regulatory documents as Markdown files

This is a repository of Markdown files, created from converting PDF files in EPARs and EPAR webpages at <https://www.ema.europa.eu/>. The sub-directories indicate the type of document.

For conversion, docling was used with rapidocr and otherwise quite standard settings. The generated Markdown files include a YAML header with metadata about the source file, e.g. URL and number of pages, as well as metadata on the conversion, e.g. docling version and processing time.

Source files are obtained at least once a week from the [European Medicines Agency (EMA)](https://www.ema.europa.eu/en/medicines). The EMA is acknowledged as a source of information used here and should also be acknowledged by users.

The correctness of information in the Markdown files is not guaranteed to be correct. Extraction from PDF files and webpages is error-prone. Users have to verify the information they use.

When using any Markdown file from this repository or offering, please include the citation

> Herold, R. (2026). Regulatory documents as Markdown files \[Data set\]. https://github.com/rfhb/emamds

See <https://regulatorysciencedata.eu/posts/emamds/> for documentation, examples, use cases and how to contribute.
