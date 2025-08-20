---
title: "page_add_text"
second_title: Aspose.PDF for Rust via C++
description: "Adds text to a page."
type: docs
url: /rust-cpp/organize/page_add_text/
---

_Adds text to a page._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Add text on page
    pdf.page_add_text(1, "added text")?;

    // Save the previously opened PDF-document
    pdf.save()?;

    Ok(())
}

```