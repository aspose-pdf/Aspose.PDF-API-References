---
title: "remove_annotations"
second_title: Aspose.PDF for Rust via C++
description: "Removes annotations from PDF-document."
type: docs
url: /rust-cpp/organize/remove_annotations/
---

_Removes annotations from PDF-document._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Remove annotations from PDF-document
    pdf.remove_annotations()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```