---
title: "grayscale"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit le document PDF en noir et blanc."
type: docs
url: /fr/rust-cpp/organize/grayscale/
---

_Convertit le document PDF en noir et blanc._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // Convertir le document PDF en noir et blanc
    pdf.grayscale()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```