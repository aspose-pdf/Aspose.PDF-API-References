---
title: "set_permissions"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "تعيين الأذونات لمستند PDF."
type: docs
url: /ar/rust-cpp/security/set_permissions/
---

_حدد الأذونات لـ PDF-document._

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
    // إنشاء مستند PDF-document جديد
    let pdf = Document::new()?;

    // تعيين الأذونات لمستند PDF.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // احفظ PDF-document مع الأذونات المحدثة
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```