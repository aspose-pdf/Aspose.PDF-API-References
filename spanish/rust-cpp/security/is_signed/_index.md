---
title: "is_signed"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtener el estado de firma del PDF-document."
type: docs
url: /es/rust-cpp/security/is_signed/
---

_Obtener el estado firmado del PDF-document._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-document llamado "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Obtener el estado firmado del PDF-document
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```