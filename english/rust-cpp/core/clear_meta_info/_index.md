---
title: "clear_meta_info"
second_title: Aspose.PDF for Rust via C++
description: "Clears all meta information values of PDF-document."
type: docs
url: /rust-cpp/core/clear_meta_info/
---

_Clears all meta information values of PDF-document._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Clear all meta information values of PDF-document
    pdf.clear_meta_info()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```