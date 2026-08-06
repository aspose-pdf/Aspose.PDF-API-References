---
title: "save_as"
second_title: "Aspose.PDF pour Rust via C++"
description: "Enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier."
type: docs
url: /fr/rust-cpp/core/save_as/
---

_Enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
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
    // Créer un nouveau PDF-document
    let pdf = Document::new()?;

    // Enregistrer le PDF-document avec un nouveau nom de fichier
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```