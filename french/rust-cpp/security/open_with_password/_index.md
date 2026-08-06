---
title: "open_with_password"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ouvrir un PDF-document protégé par mot de passe."
type: docs
url: /fr/rust-cpp/security/open_with_password/
---

_Ouvrir un document PDF protégé par mot de passe._

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
    // Ouvrir un document PDF protégé par mot de passe
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // en cours...

    Ok(())
}

```