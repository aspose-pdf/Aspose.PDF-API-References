---
title: "remove_bookmarks"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les signets du PDF-document."
type: docs
url: /fr/rust-cpp/organize/remove_bookmarks/
---

_Supprime les signets du PDF-document._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
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

    // Supprimer les signets du document PDF
    pdf.remove_bookmarks()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```