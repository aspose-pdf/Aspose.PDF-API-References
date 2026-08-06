---
title: "remove_text_footers"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les pieds de page texte du document PDF."
type: docs
url: /fr/rust-cpp/organize/remove_text_footers/
---

_Supprime les pieds de page texte du document PDF._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // Supprimer les pieds de page texte du document PDF
    pdf.remove_text_footers()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```