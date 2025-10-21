---
title: "split"
second_title: Aspose.PDF for Rust via C++
description: "Creates multiple new PDF-documents by extracting pages from the current PDF-document."
type: docs
url: /rust-cpp/core/split/
---

_Creates multiple new PDF-documents by extracting pages from the current PDF-document._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
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

    // Create multiple new PDF-documents by extracting pages from the current PDF-document
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Save each split part as a separate PDF-document
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```