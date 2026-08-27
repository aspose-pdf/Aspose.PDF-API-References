---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce se un documento PDF è conforme a PDF/A."
type: docs
url: /it/rust-cpp/organize/is_pdfa_compliant/
---

_Restituisce se un documento PDF è conforme a PDF/A._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ottieni lo stato di conformità PDF/A del documento PDF
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```