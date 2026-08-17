---
title: "reverse_pages"
second_title: Aspose.PDF for Rust via C++
description: "Reverses the order of pages in PDF-document."
type: docs
url: /rust-cpp/organize/reverse_pages/
---

_Reverses the order of pages in PDF-document._

```rust
pub fn reverse_pages(&self) -> Result<(), PdfError>
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

    // Reverse the order of pages in PDF-document
    pdf.reverse_pages()?;

    // Save the modified PDF-document with a new filename
    pdf.save_as("sample_reverse_pages.pdf")?;

    Ok(())
}

```