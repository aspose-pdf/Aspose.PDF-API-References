---
title: "remove_blank_pages"
second_title: Aspose.PDF for Rust via C++
description: "Removes blank pages from PDF-document."
type: docs
url: /rust-cpp/organize/remove_blank_pages/
---

_Removes blank pages from PDF-document._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Remove blank pages from PDF-document
    pdf.remove_blank_pages()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```