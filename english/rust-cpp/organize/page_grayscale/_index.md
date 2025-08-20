---
title: "page_grayscale"
second_title: Aspose.PDF for Rust via C++
description: "Converts a page to black and white."
type: docs
url: /rust-cpp/organize/page_grayscale/
---

_Converts a page to black and white._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Convert page to black and white
    pdf.page_grayscale(1)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```