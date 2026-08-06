---
title: "clear_meta_info"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime toutes les valeurs des métadonnées du document PDF."
type: docs
url: /fr/rust-cpp/core/clear_meta_info/
---

_Supprime toutes les valeurs des métadonnées du document PDF._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Supprimer toutes les valeurs des métadonnées du document PDF
    pdf.clear_meta_info()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```