---
title: "add_text_header"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute du texte dans l'en-tête d'un PDF-document."
type: docs
url: /fr/rust-cpp/organize/add_text_header/
---

_Ajoute du texte dans l'en-tête d'un PDF-document._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Ajouter du texte dans l'en-tête d'un document PDF
    pdf.add_text_header("HEADER")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```