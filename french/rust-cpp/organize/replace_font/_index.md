---
title: "replace_font"
second_title: "Aspose.PDF pour Rust via C++"
description: "Remplace la police dans un PDF-document."
type: docs
url: /fr/rust-cpp/organize/replace_font/
---

_Remplace la police dans un PDF-document._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Remplacer la police dans un PDF-document.
    pdf.replace_font("Helvetica", "Courier")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```