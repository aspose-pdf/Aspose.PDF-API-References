---
title: "remove_attachments"
second_title: Aspose.PDF for Rust via C++
description: "Removes attachments from PDF-document."
type: docs
url: /rust-cpp/organize/remove_attachments/
---

_Removes attachments from PDF-document._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // Remove attachments from PDF-document
    pdf.remove_attachments()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```