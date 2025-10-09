---
title: "page_is_blank"
second_title: Aspose.PDF for Rust via C++
description: "Returns page is blank in PDF-document."
type: docs
url: /rust-cpp/core/page_is_blank/
---

_Returns page is blank in PDF-document._

```rust
pub fn page_is_blank(&self) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Specify the page number (1-based index)
    let page_number = 1;

    // Return page is blank in PDF-document
    let is_blank = pdf.page_is_blank(page_number)?;

    // Print if the specified page is blank
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```