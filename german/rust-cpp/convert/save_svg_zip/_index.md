---
title: "save_svg_zip"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein SVG-Archiv."
type: docs
url: /de/rust-cpp/convert/save_svg_zip/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein SVG-Archiv._

```rust
pub fn save_svg_zip(&self, filename: &str) -> Result<(), PdfError>
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

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als SVG-Archiv
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```