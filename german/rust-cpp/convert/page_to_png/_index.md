---
title: "page_to_png"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert die angegebene Seite als PNG-Bild."
type: docs
url: /de/rust-cpp/convert/page_to_png/
---

_Konvertiert und speichert die angegebene Seite als PNG-Bild._

```rust
pub fn page_to_png(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Konvertiere und speichere die angegebene Seite als Png-Bild
    pdf.page_to_png(1, 100, "sample_page1.png")?;

    Ok(())
}

```