---
title: "save_booklet"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein Booklet-PDF-Dokument."
type: docs
url: /de/rust-cpp/convert/save_booklet/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein Booklet-PDF-Dokument._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als Booklet-PDF-Dokument
    pdf.save_booklet("sample_booklet.pdf")?;

    Ok(())
}
```