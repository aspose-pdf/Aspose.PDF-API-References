---
title: "save_tiff"
second_title: Aspose.PDF for Rust via C++
description: "Converts and saves the previously opened PDF-document as a Tiff-document."
type: docs
url: /rust-cpp/convert/save_tiff/
---

_Converts and saves the previously opened PDF-document as a Tiff-document._

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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Convert and save the previously opened PDF-document as Tiff-document
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```