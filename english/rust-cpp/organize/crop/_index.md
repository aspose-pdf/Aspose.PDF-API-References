---
title: "crop"
second_title: Aspose.PDF for Rust via C++
description: "Crops pages of a PDF-document."
type: docs
url: /rust-cpp/organize/crop/
---

_Crops pages of a PDF-document._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Crop pages of a PDF-document
    pdf.crop(10.5)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```