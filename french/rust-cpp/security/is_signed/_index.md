---
title: "is_signed"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtenir le statut de signature du PDF-document."
type: docs
url: /fr/rust-cpp/security/is_signed/
---

_Obtenir le statut signé du PDF-document._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un document PDF nommé "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Obtenir le statut signé du PDF-document
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```