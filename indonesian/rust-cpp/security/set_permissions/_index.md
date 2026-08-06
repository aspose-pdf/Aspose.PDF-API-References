---
title: "set_permissions"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Atur izin untuk dokumen PDF."
type: docs
url: /id/rust-cpp/security/set_permissions/
---

_Atur izin untuk dokumen PDF._

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
    // Buat dokumen PDF baru
    let pdf = Document::new()?;

    // Atur izin untuk dokumen PDF.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Simpan dokumen PDF dengan izin yang diperbarui
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```