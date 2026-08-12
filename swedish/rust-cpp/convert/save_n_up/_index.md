---
title: "save_n_up"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-document som ett N-Up PDF-document."
type: docs
url: /sv/rust-cpp/convert/save_n_up/
---

_Konverterar och sparar det tidigare öppnade PDF-document som ett N-Up PDF-document._

```rust
pub fn save_n_up(&self, filename: &str, columns: i32, rows: i32) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file
  * **columns** - the number of columns
  * **rows** - the number of rows

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara det tidigare öppnade PDF-document som N-Up PDF-document
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```