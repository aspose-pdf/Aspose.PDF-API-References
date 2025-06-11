---
title: "optimize_resource"
second_title: Aspose.PDF for Rust via C++
description: "Optimizes resources of the PDF-document."
type: docs
url: /rust-cpp/organize/optimize_resource/
---

_Optimizes resources of the PDF-document._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Optimize resources of PDF-document
    pdf.optimize_resource()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```