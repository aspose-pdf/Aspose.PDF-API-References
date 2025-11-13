---
title: "remove_watermarks"
second_title: Aspose.PDF for Rust via C++
description: "Removes watermarks from PDF-document."
type: docs
url: /rust-cpp/organize/remove_watermarks/
---

_Removes watermarks from PDF-document._

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // Remove watermarks from PDF-document
    pdf.remove_watermarks()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```