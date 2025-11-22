---
title: "optimize_file_size"
second_title: Aspose.PDF for Rust via C++
description: "Optimizes size of PDF-document with image compression quality."
type: docs
url: /rust-cpp/organize/optimize_file_size/
---

_Optimizes size of PDF-document with image compression quality._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Optimize size of PDF-document with image compression quality
    pdf.optimize_file_size(50)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```