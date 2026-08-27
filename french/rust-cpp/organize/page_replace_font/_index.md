---
title: "page_remplacer_police"
second_title: "Aspose.PDF pour Rust via C++"
description: "Remplace la police dans la page."
type: docs
url: /fr/rust-cpp/organize/page_replace_font/
---

_Remplace la police dans la page._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Remplacer la police dans la page
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```