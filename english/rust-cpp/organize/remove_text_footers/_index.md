---
title: "remove_text_footers"
second_title: Aspose.PDF for Rust via C++
description: "Removes text footers from PDF-document."
type: docs
url: /rust-cpp/organize/remove_text_footers/
---

_Removes text footers from PDF-document._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // Remove text footers from PDF-document
    pdf.remove_text_footers()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```