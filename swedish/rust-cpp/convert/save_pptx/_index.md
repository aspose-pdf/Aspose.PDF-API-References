---
title: "save_pptx"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett PPTX-dokument."
type: docs
url: /sv/rust-cpp/convert/save_pptx/
---

_Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett PPTX-dokument._

```rust
pub fn save_pptx(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara det tidigare öppnade PDF-dokumentet som PPTX-dokument
    pdf.save_pptx("sample.pptx")?;

    Ok(())
}

```