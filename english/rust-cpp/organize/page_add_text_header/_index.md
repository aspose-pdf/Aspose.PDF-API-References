---
title: "page_add_text_header"
second_title: Aspose.PDF for Rust via C++
description: "Adds text in page header."
type: docs
url: /rust-cpp/organize/page_add_text_header/
---

_Adds text in page header._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Add text in page header
    pdf.page_add_text_header(1, "HEADER")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```