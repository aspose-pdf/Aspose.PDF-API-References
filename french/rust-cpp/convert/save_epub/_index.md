---
title: "save_epub"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le PDF-document précédemment ouvert en tant que document EPUB."
type: docs
url: /fr/rust-cpp/convert/save_epub/
---

_Convertit et enregistre le PDF-document précédemment ouvert en tant que document EPUB._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Convertir et enregistrer le PDF-document précédemment ouvert en tant que document Epub
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```