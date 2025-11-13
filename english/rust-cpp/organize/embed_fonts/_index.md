---
title: "embed_fonts"
second_title: Aspose.PDF for Rust via C++
description: "Embeds fonts a PDF-document."
type: docs
url: /rust-cpp/organize/embed_fonts/
---

_Embeds fonts a PDF-document._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // Embed fonts a PDF-document
    pdf.embed_fonts()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```