---
title: "page_supprimer_annotations"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les annotations dans la page."
type: docs
url: /fr/rust-cpp/organize/page_remove_annotations/
---

_Supprime les annotations dans la page._

```rust
pub fn page_remove_annotations(&self, num: i32) -> Result<(), PdfError>
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

    // Supprimer les annotations dans la page
    pdf.page_remove_annotations(1)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_remove_annotations.pdf")?;

    Ok(())
}

```