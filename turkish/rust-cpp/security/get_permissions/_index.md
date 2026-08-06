---
title: "get_permissions"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının mevcut izinlerini al."
type: docs
url: /tr/rust-cpp/security/get_permissions/
---

_PDF-document mevcut izinlerini al._

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
    // Şifre korumalı bir PDF-document aç
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // PDF-document mevcut izinlerini al
    let permissions: Permissions = pdf.get_permissions()?;

    // İzinleri yazdır
    println!("Permissions: {}", permissions);

    Ok(())
}

```