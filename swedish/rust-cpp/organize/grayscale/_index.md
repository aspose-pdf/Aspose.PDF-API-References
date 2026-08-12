---
title: "grayscale"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar PDF-dokumentet till svartvitt."
type: docs
url: /sv/rust-cpp/organize/grayscale/
---

_Konverterar PDF-dokumentet till svartvitt._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera PDF-dokumentet till svartvitt
    pdf.grayscale()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```