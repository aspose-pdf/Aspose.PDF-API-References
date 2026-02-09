---
title: "page_crop"
second_title: Aspose.PDF for Rust via C++
description: "Crops a page."
type: docs
url: /rust-cpp/organize/page_crop/
---

_Crops a page._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Crop a page
    pdf.page_crop(1, 1.0)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```