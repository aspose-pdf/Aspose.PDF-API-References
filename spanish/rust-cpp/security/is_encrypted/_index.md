---
title: "is_encrypted"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtener el estado cifrado del PDF-document."
type: docs
url: /es/rust-cpp/security/is_encrypted/
---

_Obtener estado cifrado del PDF-document._

```rust
pub fn is_encrypted(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-document protegido con contraseña
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Obtener estado cifrado del PDF-document
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```