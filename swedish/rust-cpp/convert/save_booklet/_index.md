---
title: "save_booklet"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett häfte PDF-dokument."
type: docs
url: /sv/rust-cpp/convert/save_booklet/
---

_Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett häfte PDF-dokument._

```rust
pub fn save_booklet(&self, filename: &str) -> Result<(), PdfError>
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

    // Konvertera och spara det tidigare öppnade PDF-dokumentet som häfte PDF-dokument
    pdf.save_booklet("sample_booklet.pdf")?;

    Ok(())
}
```