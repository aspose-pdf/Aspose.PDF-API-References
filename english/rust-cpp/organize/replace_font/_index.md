---
title: "replace_font"
second_title: Aspose.PDF for Rust via C++
description: "Replaces font in a PDF-document."
type: docs
url: /rust-cpp/organize/replace_font/
---

_Replaces font in a PDF-document._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Replace font in a PDF-document.
    pdf.replace_font("Helvetica", "Courier")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```