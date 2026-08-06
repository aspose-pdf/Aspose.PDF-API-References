---
title: "set_permissions"
second_title: "Aspose.PDF för Rust via C++"
description: "Ange behörigheter för PDF-dokument."
type: docs
url: /sv/rust-cpp/security/set_permissions/
---

_Ställ in behörigheter för PDF-dokument._

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
    // Skapa ett nytt PDF-dokument
    let pdf = Document::new()?;

    // Ange behörigheter för PDF-dokument.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Spara PDF-dokumentet med de uppdaterade behörigheterna
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```