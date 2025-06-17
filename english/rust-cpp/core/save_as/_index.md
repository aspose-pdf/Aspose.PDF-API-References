---
title: "save_as"
second_title: Aspose.PDF for Rust via C++
description: "Saves the previously opened PDF-document with a new filename."
type: docs
url: /rust-cpp/core/save_as/
---

_Saves the previously opened PDF-document with a new filename._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** – the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Create a new PDF-document
    let pdf = Document::new()?;

    // Save the PDF-document with new filename
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```