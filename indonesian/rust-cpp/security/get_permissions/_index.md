---
title: "get_permissions"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Dapatkan izin saat ini dari dokumen PDF."
type: docs
url: /id/rust-cpp/security/get_permissions/
---

_Dapatkan izin saat ini dari PDF-document._

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
    // Buka PDF-document yang dilindungi kata sandi
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Dapatkan izin saat ini dari PDF-document
    let permissions: Permissions = pdf.get_permissions()?;

    // Cetak izin
    println!("Permissions: {}", permissions);

    Ok(())
}

```