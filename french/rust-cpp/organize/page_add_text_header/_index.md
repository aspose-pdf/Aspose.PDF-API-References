---
title: "page_add_text_header"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute du texte dans l'en-tête de page."
type: docs
url: /fr/rust-cpp/organize/page_add_text_header/
---

_Ajoute du texte dans l'en-tête de page._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Ajouter du texte dans l'en-tête de la page
    pdf.page_add_text_header(1, "HEADER")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```