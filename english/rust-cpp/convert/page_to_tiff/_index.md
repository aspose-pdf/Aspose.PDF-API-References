---
title: "page_to_tiff"
second_title: Aspose.PDF for Rust via C++
description: "Converts and saves the specified page as a TIFF-image."
type: docs
url: /rust-cpp/convert/page_to_tiff/
---

_Converts and saves the specified page as a TIFF-image._

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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Convert and save the specified page as Tiff-image
    pdf.page_to_tiff(1, 100, "sample_page1.tiff")?;

    Ok(())
}

```