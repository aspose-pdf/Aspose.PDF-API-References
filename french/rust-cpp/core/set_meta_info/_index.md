---
title: "set_meta_info"
second_title: "Aspose.PDF pour Rust via C++"
description: "Définit la valeur des métadonnées du document PDF."
type: docs
url: /fr/rust-cpp/core/set_meta_info/
---

_Définit la valeur des métadonnées du document PDF._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Définir la valeur des métadonnées du document PDF
    pdf.set_meta_info("Author", "Aspose")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```