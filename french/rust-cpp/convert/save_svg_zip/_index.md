---
title: "save_svg_zip"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le PDF-document précédemment ouvert en tant qu'archive SVG."
type: docs
url: /fr/rust-cpp/convert/save_svg_zip/
---

_Convertit et enregistre le PDF-document précédemment ouvert en tant qu'archive SVG._

```rust
pub fn save_svg_zip(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir et enregistrer le PDF-document précédemment ouvert en tant qu'archive SVG
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```