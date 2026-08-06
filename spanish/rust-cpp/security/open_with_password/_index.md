---
title: "open_with_password"
second_title: "Aspose.PDF para Rust vía C++"
description: "Abrir un PDF-document protegido con contraseña."
type: docs
url: /es/rust-cpp/security/open_with_password/
---

_Abrir un PDF-document protegido con contraseña._

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
    // Abrir un PDF-document protegido con contraseña
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // trabajando...

    Ok(())
}

```