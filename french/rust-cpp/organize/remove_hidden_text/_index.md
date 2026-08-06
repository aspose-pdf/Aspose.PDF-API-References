---
title: "remove_hidden_text"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime le texte masqué du PDF-document."
type: docs
url: /fr/rust-cpp/organize/remove_hidden_text/
---

_Supprime le texte masqué du PDF-document._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Supprimer le texte masqué du document PDF
    pdf.remove_hidden_text()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```