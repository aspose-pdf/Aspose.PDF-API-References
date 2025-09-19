---
title: "save_svg_zip"
second_title: Aspose.PDF for Rust via C++
description: "Converts and saves the previously opened PDF-document as a SVG-archive."
type: docs
url: /rust-cpp/convert/save_svg_zip/
---

_Converts and saves the previously opened PDF-document as a SVG-archive._

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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Convert and save the previously opened PDF-document as SVG-archive
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```