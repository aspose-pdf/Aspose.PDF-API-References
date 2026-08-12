---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtiene si un documento PDF es compatible con PDF/UA."
type: docs
url: /es/rust-cpp/organize/is_pdfua_compliant/
---

_Obtiene si un documento PDF es compatible con PDF/UA._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Obtén el estado de compatibilidad PDF/UA del documento PDF
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```