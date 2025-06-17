---
title: "optimize"
second_title: Aspose.PDF for Rust via C++
description: "Optimizes PDF-document content."
type: docs
url: /rust-cpp/organize/optimize/
---

_Optimizes PDF-document content._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Optimize PDF-document content
    pdf.optimize()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```