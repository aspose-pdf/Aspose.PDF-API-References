---
title: "page_to_tiff"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre la page spécifiée en tant qu'image TIFF."
type: docs
url: /fr/rust-cpp/convert/page_to_tiff/
---

_Convertit et enregistre la page spécifiée en tant qu'image TIFF._

```rust
pub fn page_to_tiff(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Convertir et enregistrer la page spécifiée en tant qu'image Tiff
    pdf.page_to_tiff(1, 100, "sample_page1.tiff")?;

    Ok(())
}

```