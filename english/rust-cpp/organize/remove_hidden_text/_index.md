---
title: "remove_hidden_text"
second_title: Aspose.PDF for Rust via C++
description: "Removes hidden text from PDF-document."
type: docs
url: /rust-cpp/organize/remove_hidden_text/
---

_Removes hidden text from PDF-document._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Remove hidden text from PDF-document
    pdf.remove_hidden_text()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```