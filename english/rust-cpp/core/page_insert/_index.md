---
title: "page_insert"
second_title: Aspose.PDF for Rust via C++
description: "Inserts a new page at the specified position in the PDF-document."
type: docs
url: /rust-cpp/core/page_insert/
---

_Inserts a new page at the specified position in the PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Insert new page at the specified position in PDF-document
    pdf.page_insert(1)?;

    // Save the previously opened PDF-document
    pdf.save()?;

    Ok(())
}

```