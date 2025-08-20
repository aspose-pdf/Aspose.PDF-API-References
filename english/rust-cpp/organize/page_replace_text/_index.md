---
title: "page_replace_text"
second_title: Aspose.PDF for Rust via C++
description: "Replaces text on page."
type: docs
url: /rust-cpp/organize/page_replace_text/
---

_Replaces text on page._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Replace text on page
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```