---
title: "get_permissions"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtener los permisos actuales del PDF-document."
type: docs
url: /es/rust-cpp/security/get_permissions/
---

_Obtener permisos actuales del PDF-document._

```rust
pub fn get_permissions(&self) -> Result<Permissions, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Permissions)** - the bitmask of permissions, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-document protegido con contraseña
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Obtener permisos actuales del PDF-document
    let permissions: Permissions = pdf.get_permissions()?;

    // Imprimir permisos
    println!("Permissions: {}", permissions);

    Ok(())
}

```