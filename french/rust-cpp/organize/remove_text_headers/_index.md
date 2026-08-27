---
title: "remove_text_headers"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les en-têtes de texte du PDF-document."
type: docs
url: /fr/rust-cpp/organize/remove_text_headers/
---

_Supprime les en-têtes de texte du PDF-document._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Supprimer les en-têtes de texte du PDF-document
    pdf.remove_text_headers()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```