---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottiene se un PDF-document è conforme a PDF/UA."
type: docs
url: /it/rust-cpp/organize/is_pdfua_compliant/
---

_Ottiene se un PDF-document è conforme a PDF/UA._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ottieni lo stato di conformità PDF/UA del PDF-document
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```