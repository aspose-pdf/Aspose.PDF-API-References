---
title: "replace_text"
second_title: "Aspose.PDF pour Rust via C++"
description: "Remplace le texte."
type: docs
url: /fr/rust-cpp/organize/replace_text/
---

_Remplace le texte._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Remplacer le texte dans le document PDF
    pdf.replace_text("PDF", "TXT")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```