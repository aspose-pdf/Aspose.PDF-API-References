---
title: "unembed_fonts"
second_title: "Aspose.PDF för Rust via C++"
description: "Avbäddar typsnitt i ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/unembed_fonts/
---

_Avbäddar typsnitt i ett PDF-dokument._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Avbädda typsnitt i ett PDF-dokument
    pdf.unembed_fonts()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```