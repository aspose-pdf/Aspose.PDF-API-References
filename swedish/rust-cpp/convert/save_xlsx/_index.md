---
title: "save_xlsx"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett XLSX-dokument."
type: docs
url: /sv/rust-cpp/convert/save_xlsx/
---

_Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett XLSX-dokument._

```rust
pub fn save_xlsx(&self, filename: &str) -> Result<(), PdfError>
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

    // Konvertera och spara det tidigare öppnade PDF-dokumentet som XlsX-dokument
    pdf.save_xlsx("sample.xlsx")?;

    Ok(())
}

```