---
title: "is_encrypted"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtenir le statut de chiffrement du PDF-document."
type: docs
url: /fr/rust-cpp/security/is_encrypted/
---

_Obtenir le statut chiffré du document PDF._

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
    // Ouvrir un document PDF protégé par mot de passe
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Obtenir le statut chiffré du document PDF
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```