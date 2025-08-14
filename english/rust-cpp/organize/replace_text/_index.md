---
title: "replace_text"
second_title: Aspose.PDF for Rust via C++
description: "Replaces text."
type: docs
url: /rust-cpp/organize/replace_text/
---

_Replaces text._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Replace text in PDF-document
    pdf.replace_text("PDF", "TXT")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```