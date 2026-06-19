---
title: "is_linearized"
second_title: Aspose.PDF for Rust via C++
description: "Gets a value indicating whether document is linearized."
type: docs
url: /rust-cpp/core/is_linearized/
---

_Gets a value indicating whether document is linearized._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Get a value indicating whether document is linearized
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```