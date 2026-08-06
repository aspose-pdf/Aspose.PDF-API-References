---
title: "Şifre Çöz"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının şifresini çöz."
type: docs
url: /tr/rust-cpp/security/decrypt/
---

_PDF-document şifresini çöz._

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Şifre korumalı bir PDF-document aç
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // PDF-document şifresini çöz
    pdf.decrypt()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```