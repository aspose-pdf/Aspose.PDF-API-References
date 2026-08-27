---
title: "embed_fonts"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Incorpora caratteri in un PDF-document."
type: docs
url: /it/rust-cpp/organize/embed_fonts/
---

_Incorpora caratteri in un PDF-document._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Incorpora caratteri in un PDF-document
    pdf.embed_fonts()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```