---
title: "is_signed"
second_title: Aspose.PDF for Rust via C++
description: "Get signed status of PDF-document."
type: docs
url: /rust-cpp/security/is_signed/
---

_Get signed status of PDF-document._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document named "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Get signed status of PDF-document
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```