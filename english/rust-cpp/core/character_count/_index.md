---
title: "character_count"
second_title: Aspose.PDF for Rust via C++
description: "Returns character count in PDF-document."
type: docs
url: /rust-cpp/core/character_count/
---

_Returns character count in PDF-document._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Return character count in PDF-document
    let count = pdf.character_count()?;

    // Print the character count
    println!("Character count: {}", count);

    Ok(())
}

```