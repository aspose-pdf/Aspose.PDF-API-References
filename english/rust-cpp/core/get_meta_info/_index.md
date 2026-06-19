---
title: "get_meta_info"
second_title: Aspose.PDF for Rust via C++
description: "Gets meta information value of PDF-document."
type: docs
url: /rust-cpp/core/get_meta_info/
---

_Gets meta information value of PDF-document._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Get meta information value of PDF-document
    let author = pdf.get_meta_info("Author")?;

    // Print the result
    println!("Author: {}", author);

    Ok(())
}

```