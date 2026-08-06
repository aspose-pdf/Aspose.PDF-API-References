---
title: "add_text_footer"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute du texte dans le pied de page d'un PDF-document."
type: docs
url: /fr/rust-cpp/organize/add_text_footer/
---

_Ajoute du texte dans le pied de page d'un PDF-document._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Ajouter du texte dans le pied de page d'un document PDF
    pdf.add_text_footer("FOOTER")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```