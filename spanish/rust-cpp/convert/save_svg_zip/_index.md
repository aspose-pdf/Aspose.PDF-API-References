---
title: "save_svg_zip"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el PDF-document previamente abierto como un SVG-archive."
type: docs
url: /es/rust-cpp/convert/save_svg_zip/
---

_Convierte y guarda el PDF-document previamente abierto como un SVG-archive._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Convertir y guardar el PDF-document previamente abierto como SVG-archive
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```