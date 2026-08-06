---
title: "set_permissions"
second_title: "Aspose.PDF для Rust через C++"
description: "Установить разрешения для PDF-документа."
type: docs
url: /ru/rust-cpp/security/set_permissions/
---

_Установить разрешения для PDF-документа._

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
    // Создайте новый PDF-документ
    let pdf = Document::new()?;

    // Установить разрешения для PDF-документа.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // Сохранить PDF-документ с обновлёнными разрешениями
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```