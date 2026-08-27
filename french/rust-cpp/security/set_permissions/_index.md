---
title: "set_permissions"
second_title: "Aspose.PDF pour Rust via C++"
description: "Définir les autorisations pour le PDF-document."
type: docs
url: /fr/rust-cpp/security/set_permissions/
---

_Définir les autorisations pour le PDF-document._

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
    // Créer un nouveau PDF-document
    let pdf = Document::new()?;

    // Définir les autorisations pour le PDF-document.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Enregistrer le PDF-document avec les autorisations mises à jour
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```