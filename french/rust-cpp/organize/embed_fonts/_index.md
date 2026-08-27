---
title: "embed_fonts"
second_title: "Aspose.PDF pour Rust via C++"
description: "Intègre les polices dans un PDF-document."
type: docs
url: /fr/rust-cpp/organize/embed_fonts/
---

_Intègre les polices dans un PDF-document._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // Intégrer les polices dans un PDF-document
    pdf.embed_fonts()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```