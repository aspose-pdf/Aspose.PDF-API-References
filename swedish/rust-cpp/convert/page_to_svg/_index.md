---
title: "page_to_svg"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar den angivna sidan som en SVG-image."
type: docs
url: /sv/rust-cpp/convert/page_to_svg/
---

_Konverterar och sparar den angivna sidan som en SVG-image._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara den angivna sidan som Svg-image
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```