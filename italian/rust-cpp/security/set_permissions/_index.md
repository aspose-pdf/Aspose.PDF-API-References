---
title: "set_permissions"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Imposta i permessi per il PDF-document."
type: docs
url: /it/rust-cpp/security/set_permissions/
---

_Imposta i permessi per PDF-document._

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
    // Crea un nuovo PDF-document
    let pdf = Document::new()?;

    // Imposta i permessi per il PDF-document.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Salva il PDF-document con i permessi aggiornati
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```