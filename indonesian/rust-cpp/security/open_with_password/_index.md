---
title: "open_with_password"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Buka dokumen PDF yang dilindungi kata sandi."
type: docs
url: /id/rust-cpp/security/open_with_password/
---

_Buka PDF-document yang dilindungi kata sandi._

```rust
pub fn open_with_password(filename: &str, password: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open
  * **password** - user/owner password of the password-protected PDF-document

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document yang dilindungi kata sandi
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // sedang bekerja...

    Ok(())
}

```