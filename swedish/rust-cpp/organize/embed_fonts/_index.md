---
title: "embed_fonts"
second_title: "Aspose.PDF för Rust via C++"
description: "Inbäddar teckensnitt i ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/embed_fonts/
---

_Inbäddar teckensnitt i ett PDF-dokument._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Inbädda teckensnitt i ett PDF-dokument
    pdf.embed_fonts()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```