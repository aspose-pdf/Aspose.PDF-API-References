---
title: "is_linearized"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtiene un valor que indica si el documento está linealizado."
type: docs
url: /es/rust-cpp/core/is_linearized/
---

_Obtiene un valor que indica si el documento está linealizado._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
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

    // Obtener un valor que indica si el documento está linealizado
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```