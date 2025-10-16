---
title: "append_pages"
second_title: Aspose.PDF for Rust via C++
description: "Appends selected pages from another PDF-document."
type: docs
url: /rust-cpp/core/append_pages/
---

_Appends selected pages from another PDF-document._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open the primary PDF-document
    let pdf = Document::open("sample1page.pdf")?;

    // Open another PDF-document to append
    let another_pdf = Document::open("sample.pdf")?;

    // Append specific pages (1 and 3) from another PDF-document
    pdf.append_pages(&another_pdf, "1,3")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```