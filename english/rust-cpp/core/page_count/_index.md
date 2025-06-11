---
title: "page_count"
second_title: Aspose.PDF for Rust via C++
description: "Returns the number of pages in the PDF-document."
type: docs
url: /rust-cpp/core/page_count/
---

_Returns the number of pages in the PDF-document._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
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

    // Return page count in PDF-document
    let count = pdf.page_count()?;

    // Print the page count
    println!("Count: {}", count);

    Ok(())
}

```