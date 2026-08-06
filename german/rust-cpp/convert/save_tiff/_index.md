---
title: "save_tiff"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein Tiff-Dokument."
type: docs
url: /de/rust-cpp/convert/save_tiff/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein Tiff-Dokument._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als Tiff-Dokument
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```