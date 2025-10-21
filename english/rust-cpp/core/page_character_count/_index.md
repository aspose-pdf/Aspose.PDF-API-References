---
title: "page_character_count"
second_title: Aspose.PDF for Rust via C++
description: "Returns character count on specified page in PDF-document."
type: docs
url: /rust-cpp/core/page_character_count/
---

_Returns character count on specified page in PDF-document._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
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

    // Return character count on the specified page
    let count = pdf.page_character_count(page_number)?;

    // Print the character count
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```