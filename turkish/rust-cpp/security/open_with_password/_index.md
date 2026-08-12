---
title: "open_with_password"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Şifre korumalı bir PDF-dökümanını aç."
type: docs
url: /tr/rust-cpp/security/open_with_password/
---

_Şifre korumalı bir PDF-document aç._

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
    // Şifre korumalı bir PDF-document aç
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // çalışıyor...

    Ok(())
}

```