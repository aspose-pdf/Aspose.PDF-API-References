---
title: "page_to_tiff"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar den angivna sidan som en TIFF-bild."
type: docs
url: /sv/rust-cpp/convert/page_to_tiff/
---

_Konverterar och sparar den angivna sidan som en TIFF-bild._

```rust
pub fn page_to_tiff(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara den angivna sidan som Tiff-bild
    pdf.page_to_tiff(1, 100, "sample_page1.tiff")?;

    Ok(())
}

```