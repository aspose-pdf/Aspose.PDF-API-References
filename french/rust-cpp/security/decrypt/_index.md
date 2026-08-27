---
title: "décrypter"
second_title: "Aspose.PDF pour Rust via C++"
description: "Déchiffrer le PDF-document."
type: docs
url: /fr/rust-cpp/security/decrypt/
---

_Décrypter le document PDF._

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
    // Ouvrir un document PDF protégé par mot de passe
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Décrypter le document PDF
    pdf.decrypt()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```