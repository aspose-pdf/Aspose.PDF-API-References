---
title: "page_to_jpg"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre la page spécifiée en tant qu'image JPG."
type: docs
url: /fr/rust-cpp/convert/page_to_jpg/
---

_Convertit et enregistre la page spécifiée en tant qu'image JPG._

```rust
pub fn page_to_jpg(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
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

    // Convertir et enregistrer la page spécifiée en Jpg-image
    pdf.page_to_jpg(1, 100, "sample_page1.jpg")?;

    Ok(())
}

```