---
title: "is_pdfa_compliant"
second_title: Aspose.PDF for Rust via C++
description: "Get is a PDF-document PDF/A compliant."
type: docs
url: /rust-cpp/organize/is_pdfa_compliant/
---

_Get is a PDF-document PDF/A compliant._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Get PDF/A compliant status of PDF-document
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```