---
title: "page_add_text_footer"
second_title: Aspose.PDF for Rust via C++
description: "Adds text in page footer."
type: docs
url: /rust-cpp/organize/page_add_text_footer/
---

_Adds text in page footer._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Add text in page footer
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```