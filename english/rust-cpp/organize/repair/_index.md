---
title: "repair"
second_title: Aspose.PDF for Rust via C++
description: "Repairs the PDF-document."
type: docs
url: /rust-cpp/organize/repair/
---

_Repairs the PDF-document._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // Repair PDF-document
    pdf.repair()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```