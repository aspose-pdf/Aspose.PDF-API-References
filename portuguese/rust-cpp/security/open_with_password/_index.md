---
title: "open_with_password"
second_title: "Aspose.PDF para Rust via C++"
description: "Abrir um PDF-document protegido por senha."
type: docs
url: /pt/rust-cpp/security/open_with_password/
---

_Abrir um documento PDF protegido por senha._

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
    // Abrir um documento PDF protegido por senha
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // processando...

    Ok(())
}

```