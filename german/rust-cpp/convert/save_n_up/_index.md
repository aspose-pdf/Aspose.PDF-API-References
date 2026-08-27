---
title: "save_n_up"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als N-Up-PDF-Dokument."
type: docs
url: /de/rust-cpp/convert/save_n_up/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als N-Up-PDF-Dokument._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als N-Up-PDF-Dokument
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```