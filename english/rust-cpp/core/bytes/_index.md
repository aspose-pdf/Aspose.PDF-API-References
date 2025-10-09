---
title: "bytes"
second_title: Aspose.PDF for Rust via C++
description: "Returns the contents of the PDF-document as a byte vector."
type: docs
url: /rust-cpp/core/bytes/
---

_Returns the contents of the PDF-document as a byte vector._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Create a new PDF-document
    let pdf = Document::new()?;

    // Return the contents of the PDF-document as a byte vector
    let data = pdf.bytes()?;

    // Print length of the byte vector
    println!("Length: {}", data.len());

    Ok(())
}

```