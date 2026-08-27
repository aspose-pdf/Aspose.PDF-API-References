---
title: "remove_blank_pages"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les pages blanches du PDF-document."
type: docs
url: /fr/rust-cpp/organize/remove_blank_pages/
---

_Supprime les pages blanches du PDF-document._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Supprimer les pages blanches du document PDF
    pdf.remove_blank_pages()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```