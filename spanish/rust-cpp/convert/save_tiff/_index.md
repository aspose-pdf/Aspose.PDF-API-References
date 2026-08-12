---
title: "save_tiff"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el documento PDF previamente abierto como un documento Tiff."
type: docs
url: /es/rust-cpp/convert/save_tiff/
---

_Convierte y guarda el documento PDF previamente abierto como un documento Tiff._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Convertir y guardar el documento PDF previamente abierto como documento Tiff
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```