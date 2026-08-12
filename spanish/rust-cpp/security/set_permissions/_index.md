---
title: "set_permissions"
second_title: "Aspose.PDF para Rust vía C++"
description: "Establecer permisos para el PDF-document."
type: docs
url: /es/rust-cpp/security/set_permissions/
---

_Establecer permisos para PDF-document._

```rust
pub fn set_permissions(
    &self,
    user_password: &str,
    owner_password: &str,
    permissions: Permissions,
) -> Result<(), PdfError>
```

**Arguments**
  * **user_password** - the user password
  * **owner_password** - the owner password
  * **permissions** - the allowed permissions (bitflags `Permissions`)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crear un nuevo PDF-documento
    let pdf = Document::new()?;

    // Establecer permisos para el PDF-document.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Guardar el PDF-document con los permisos actualizados
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```