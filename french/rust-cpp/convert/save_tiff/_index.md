---
title: "save_tiff"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le PDF-document précédemment ouvert en tant que document Tiff."
type: docs
url: /fr/rust-cpp/convert/save_tiff/
---

_Convertit et enregistre le PDF-document précédemment ouvert en tant que document Tiff._

```rust
pub fn save_tiff(&self, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **resolution_dpi** - the resolution in DPI
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

    // Convertir et enregistrer le PDF-document précédemment ouvert en tant que document Tiff
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```