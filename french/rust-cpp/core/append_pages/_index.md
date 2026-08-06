---
title: "append_pages"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute les pages sélectionnées d'un autre PDF-document."
type: docs
url: /fr/rust-cpp/core/append_pages/
---

_Ajoute les pages sélectionnées d'un autre PDF-document._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir le PDF-document principal
    let pdf = Document::open("sample1page.pdf")?;

    // Ouvrir un autre PDF-document à ajouter
    let another_pdf = Document::open("sample.pdf")?;

    // Ajoute les pages spécifiques (1 et 3) d'un autre PDF-document
    pdf.append_pages(&another_pdf, "1,3")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```