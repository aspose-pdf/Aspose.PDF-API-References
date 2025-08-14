---
title: "page_to_svg"
second_title: Aspose.PDF for Rust via C++
description: "Converts and saves the specified page as an SVG-image."
type: docs
url: /rust-cpp/convert/page_to_svg/
---

_Converts and saves the specified page as an SVG-image._

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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Convert and save the specified page as Svg-image
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```