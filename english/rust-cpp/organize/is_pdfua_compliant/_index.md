---
title: "is_pdfua_compliant"
second_title: Aspose.PDF for Rust via C++
description: "Gets is a PDF-document PDF/UA compliant."
type: docs
url: /rust-cpp/organize/is_pdfua_compliant/
---

_Gets is a PDF-document PDF/UA compliant._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // Get PDF/UA compliant status of PDF-document
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```