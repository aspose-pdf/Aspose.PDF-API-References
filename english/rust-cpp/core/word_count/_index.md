---
title: "word_count"
second_title: Aspose.PDF for Rust via C++
description: "Returns word count in PDF-document."
type: docs
url: /rust-cpp/core/word_count/
---

_Returns word count in PDF-document._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // Return word count in PDF-document
    let count = pdf.word_count()?;

    // Print the word count
    println!("Word count: {}", count);

    Ok(())
}

```