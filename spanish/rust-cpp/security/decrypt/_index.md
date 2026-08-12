---
title: "descifrar"
second_title: "Aspose.PDF para Rust vía C++"
description: "Descifrar el PDF-document."
type: docs
url: /es/rust-cpp/security/decrypt/
---

_Descifrar PDF-document._

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-document protegido con contraseña
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Descifrar PDF-document
    pdf.decrypt()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```