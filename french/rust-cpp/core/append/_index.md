---
title: "append"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute des pages d'un autre PDF-document."
type: docs
url: /fr/rust-cpp/core/append/
---

_Ajoute des pages d'un autre PDF-document._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir le PDF-document principal
    let pdf = Document::open("sample.pdf")?;

    // Ouvrir un autre PDF-document à ajouter
    let another_pdf = Document::open("sample1page.pdf")?;

    // Ajouter des pages d'un autre PDF-document
    pdf.append(&another_pdf)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```