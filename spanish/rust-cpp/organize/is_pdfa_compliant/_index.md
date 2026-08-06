---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtiene si un documento PDF es compatible con PDF/A."
type: docs
url: /es/rust-cpp/organize/is_pdfa_compliant/
---

_Obtiene si un documento PDF es compatible con PDF/A._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Obtener el estado de compatibilidad PDF/A del documento PDF
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```