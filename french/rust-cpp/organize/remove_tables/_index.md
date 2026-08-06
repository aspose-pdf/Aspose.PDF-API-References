---
title: "remove_tables"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime les tables du PDF-document."
type: docs
url: /fr/rust-cpp/organize/remove_tables/
---

_Supprime les tables du PDF-document._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Supprimer les tables du PDF-document
    pdf.remove_tables()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```