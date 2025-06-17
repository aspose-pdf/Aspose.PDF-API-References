---
title: "save"
second_title: Aspose.PDF for Rust via C++
description: "Saves the previously opened PDF-document."
type: docs
url: /rust-cpp/core/save/
---

_Saves the previously opened PDF-document._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document named "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Save the previously opened PDF-document
    pdf.save()?;

    Ok(())
}

```