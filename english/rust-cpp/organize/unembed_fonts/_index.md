---
title: "unembed_fonts"
second_title: Aspose.PDF for Rust via C++
description: "Unembeds fonts a PDF-document."
type: docs
url: /rust-cpp/organize/unembed_fonts/
---

_Unembeds fonts a PDF-document._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Unembed fonts a PDF-document
    pdf.unembed_fonts()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```