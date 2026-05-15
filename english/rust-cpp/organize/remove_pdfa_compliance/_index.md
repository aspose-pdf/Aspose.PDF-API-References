---
title: "remove_pdfa_compliance"
second_title: Aspose.PDF for Rust via C++
description: "Remove PDF/A compliance from a PDF-document."
type: docs
url: /rust-cpp/organize/remove_pdfa_compliance/
---

_Remove PDF/A compliance from a PDF-document._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Remove PDF/A compliance from a PDF-document
    pdf.remove_pdfa_compliance()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```