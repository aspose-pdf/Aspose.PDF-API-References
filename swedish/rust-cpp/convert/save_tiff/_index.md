---
title: "save_tiff"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett Tiff-dokument."
type: docs
url: /sv/rust-cpp/convert/save_tiff/
---

_Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett Tiff-dokument._

```rust
pub fn save_tiff(&self, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **resolution_dpi** - the resolution in DPI
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

    // Konvertera och spara det tidigare öppnade PDF-dokumentet som Tiff-dokument
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```