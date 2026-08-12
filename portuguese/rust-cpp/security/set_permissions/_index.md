---
title: "set_permissions"
second_title: "Aspose.PDF para Rust via C++"
description: "Definir permissões para PDF-document."
type: docs
url: /pt/rust-cpp/security/set_permissions/
---

_Definir permissões para PDF-document._

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
    // Crie um novo PDF-document
    let pdf = Document::new()?;

    // Definir permissões para PDF-document.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Salvar o PDF-document com as permissões atualizadas
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```