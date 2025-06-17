---
title: "page_add"
second_title: Aspose.PDF for Rust via C++
description: "Adds a new page to the PDF-document."
type: docs
url: /rust-cpp/core/page_add/
---

_Adds a new page to the PDF-document._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Add new page in PDF-document
    pdf.page_add()?;

    // Save the previously opened PDF-document
    pdf.save()?;

    Ok(())
}

```