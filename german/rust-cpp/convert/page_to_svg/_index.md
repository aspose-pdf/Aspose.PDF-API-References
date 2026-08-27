---
title: "page_to_svg"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert die angegebene Seite als SVG-Bild."
type: docs
url: /de/rust-cpp/convert/page_to_svg/
---

_Konvertiert und speichert die angegebene Seite als SVG-Bild._

```rust
pub fn page_to_svg(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Konvertiere und speichere die angegebene Seite als SVG-Bild
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```