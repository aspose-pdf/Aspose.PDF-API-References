---
title: "get_permissions"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "الحصول على الأذونات الحالية لمستند PDF."
type: docs
url: /ar/rust-cpp/security/get_permissions/
---

_احصل على الأذونات الحالية لمستند PDF._

```rust
pub fn get_permissions(&self) -> Result<Permissions, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Permissions)** - the bitmask of permissions, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF محمي بكلمة مرور
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // احصل على الأذونات الحالية لمستند PDF
    let permissions: Permissions = pdf.get_permissions()?;

    // طباعة الأذونات
    println!("Permissions: {}", permissions);

    Ok(())
}

```