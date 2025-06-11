---
title: "page_delete"
second_title: Aspose.PDF for Rust via C++
description: "Deletes the specified page from the PDF-document."
type: docs
url: /rust-cpp/core/page_delete/
---

_Deletes the specified page from the PDF-document._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** – the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Delete specified page in PDF-document
    pdf.page_delete(1)?;

    // Save the previously opened PDF-document
    pdf.save()?;

    Ok(())
}

```