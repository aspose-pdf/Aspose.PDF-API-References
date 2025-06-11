---
title: "grayscale"
second_title: Aspose.PDF for Rust via C++
description: "Converts the PDF-document to black and white."
type: docs
url: /rust-cpp/organize/grayscale/
---

_Converts the PDF-document to black and white._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // Convert PDF-document to black and white
    pdf.grayscale()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```