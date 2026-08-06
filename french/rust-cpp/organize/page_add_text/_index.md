---
title: "page_add_text"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute du texte à une page."
type: docs
url: /fr/rust-cpp/organize/page_add_text/
---

_Ajoute du texte à une page._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Ajouter du texte sur la page
    pdf.page_add_text(1, "added text")?;

    // Enregistrer le PDF-document précédemment ouvert
    pdf.save()?;

    Ok(())
}

```