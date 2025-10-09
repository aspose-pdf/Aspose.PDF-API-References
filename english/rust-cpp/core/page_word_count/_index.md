---
title: "page_word_count"
second_title: Aspose.PDF for Rust via C++
description: "Returns word count on specified page in PDF-document."
type: docs
url: /rust-cpp/core/page_word_count/
---

_Returns word count on specified page in PDF-document._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Specify the page number (1-based index)
    let page_number = 1;

    // Return word count on the specified page
    let count = pdf.page_word_count(page_number)?;

    // Print the word count
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```