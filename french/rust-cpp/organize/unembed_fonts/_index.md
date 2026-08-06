---
title: "unembed_fonts"
second_title: "Aspose.PDF pour Rust via C++"
description: "Désintègre les polices d'un PDF-document."
type: docs
url: /fr/rust-cpp/organize/unembed_fonts/
---

_Désintègre les polices d'un PDF-document._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Désintégrer les polices d'un PDF-document
    pdf.unembed_fonts()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```