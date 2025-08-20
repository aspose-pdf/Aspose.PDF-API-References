---
title: "page_add_page_num"
second_title: Aspose.PDF for Rust via C++
description: "Adds page number on page."
type: docs
url: /rust-cpp/organize/page_add_page_num/
---

_Adds page number on page._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Add page number on page
    pdf.page_add_page_num(1)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```