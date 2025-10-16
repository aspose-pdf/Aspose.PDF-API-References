---
title: "split_document"
second_title: Aspose.PDF for Rust via C++
description: "Creates multiple new PDF-documents by extracting pages from the source PDF-document."
type: docs
url: /rust-cpp/core/split_document/
---

_Creates multiple new PDF-documents by extracting pages from the source PDF-document._

```rust
pub fn split_document(document: &Document, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document named "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Creates multiple new PDF-documents by extracting pages from the source PDF-document
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // Save each split part as a separate PDF-document
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```