---
title: "page_delete"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime la page spécifiée du PDF-document."
type: docs
url: /fr/rust-cpp/core/page_delete/
---

_Supprime la page spécifiée du PDF-document._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Supprimer la page spécifiée dans le PDF-document
    pdf.page_delete(1)?;

    // Enregistrer le PDF-document précédemment ouvert
    pdf.save()?;

    Ok(())
}

```