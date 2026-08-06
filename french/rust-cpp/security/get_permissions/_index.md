---
title: "get_permissions"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtenir les autorisations actuelles du PDF-document."
type: docs
url: /fr/rust-cpp/security/get_permissions/
---

_Obtenir les autorisations actuelles du document PDF._

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
    // Ouvrir un document PDF protégé par mot de passe
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Obtenir les autorisations actuelles du document PDF
    let permissions: Permissions = pdf.get_permissions()?;

    // Afficher les autorisations
    println!("Permissions: {}", permissions);

    Ok(())
}

```