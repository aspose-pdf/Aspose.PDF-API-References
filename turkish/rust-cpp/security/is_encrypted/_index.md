---
title: "is_encrypted"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının şifrelenme durumunu al."
type: docs
url: /tr/rust-cpp/security/is_encrypted/
---

_PDF-document şifreli durumunu al._

```rust
pub fn is_encrypted(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Şifre korumalı bir PDF-document aç
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // PDF-document şifreli durumunu al
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```