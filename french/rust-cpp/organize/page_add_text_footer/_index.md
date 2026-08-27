---
title: "page_add_text_footer"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute du texte dans le pied de page."
type: docs
url: /fr/rust-cpp/organize/page_add_text_footer/
---

_Ajoute du texte dans le pied de page._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Ajouter du texte dans le pied de page de la page
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```