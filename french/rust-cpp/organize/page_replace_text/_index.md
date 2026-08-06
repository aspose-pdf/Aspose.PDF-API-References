---
title: "page_replace_text"
second_title: "Aspose.PDF pour Rust via C++"
description: "Remplace le texte sur la page."
type: docs
url: /fr/rust-cpp/organize/page_replace_text/
---

_Remplace le texte sur la page._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Remplacer le texte sur la page
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```