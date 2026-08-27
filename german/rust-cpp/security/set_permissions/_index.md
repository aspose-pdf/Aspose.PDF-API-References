---
title: "set_permissions"
second_title: "Aspose.PDF für Rust über C++"
description: "Setze Berechtigungen für das PDF-Dokument."
type: docs
url: /de/rust-cpp/security/set_permissions/
---

_Berechtigungen für PDF-Dokument festlegen._

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
    // Erstelle ein neues PDF-Dokument
    let pdf = Document::new()?;

    // Setze Berechtigungen für das PDF-Dokument.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Speichern Sie das PDF-Dokument mit den aktualisierten Berechtigungen
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```