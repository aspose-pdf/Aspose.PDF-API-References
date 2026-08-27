---
title: "optimize_file_size"
second_title: "Aspose.PDF pour Rust via C++"
description: "Optimise la taille du PDF-document avec la qualité de compression d'image."
type: docs
url: /fr/rust-cpp/organize/optimize_file_size/
---

_Optimise la taille du PDF-document avec la qualité de compression d'image._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Optimiser la taille du PDF-document avec la qualité de compression d'image
    pdf.optimize_file_size(50)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```