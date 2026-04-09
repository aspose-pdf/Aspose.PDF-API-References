---
title: "remove_signs"
second_title: Aspose.PDF for Rust via C++
description: "Remove signs from PDF-document."
type: docs
url: /rust-cpp/security/remove_signs/
---

_Remove signs from PDF-document._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document named "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Remove signs from PDF-document
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```