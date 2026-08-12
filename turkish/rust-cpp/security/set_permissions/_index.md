---
title: "set_permissions"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanı için izinleri ayarla."
type: docs
url: /tr/rust-cpp/security/set_permissions/
---

_PDF-document için izinleri ayarla._

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
    // Yeni bir PDF-document oluştur
    let pdf = Document::new()?;

    // PDF-dökümanı için izinleri ayarla.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Güncellenmiş izinlerle PDF-document'i kaydet
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```