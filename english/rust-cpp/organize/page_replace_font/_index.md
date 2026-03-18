---
title: "page_replace_font"
second_title: Aspose.PDF for Rust via C++
description: "Replaces font in page."
type: docs
url: /rust-cpp/organize/page_replace_font/
---

_Replaces font in page._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Replace font in page
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```