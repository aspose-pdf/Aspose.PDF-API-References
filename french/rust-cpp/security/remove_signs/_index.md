---
title: "remove_signs"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprimer les signatures du PDF-document."
type: docs
url: /fr/rust-cpp/security/remove_signs/
---

_Supprimer les signatures du document PDF._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un document PDF nommé "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Supprimer les signatures du document PDF
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```