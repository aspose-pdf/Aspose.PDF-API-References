---
title: "remove_pdfua_compliance"
second_title: Aspose.PDF for Rust via C++
description: "Remove PDF/UA compliance from a PDF-document."
type: docs
url: /rust-cpp/organize/remove_pdfua_compliance/
---

_Remove PDF/UA compliance from a PDF-document._

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
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

    // Remove PDF/UA compliance from a PDF-document
    pdf.remove_pdfua_compliance()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```