---
title: "page_remove_text_headers"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les en-têtes texte de la page."
type: docs
url: /fr/rust-cpp/organize/page_remove_text_headers/
---

_Supprime les en-têtes texte de la page._

```rust
pub fn page_remove_text_headers(&self, num: i32) -> Result<(), PdfError>
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

    // Supprimer les en-têtes texte de la page
    pdf.page_remove_text_headers(1)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_remove_text_headers.pdf")?;

    Ok(())
}

```