---
title: "save_xps"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el PDF-documento previamente abierto como un documento XPS."
type: docs
url: /es/rust-cpp/convert/save_xps/
---

_Convierte y guarda el PDF-documento previamente abierto como un documento XPS._

```rust
pub fn save_xps(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir y guardar el PDF-documento previamente abierto como documento Xps
    pdf.save_xps("sample.xps")?;

    Ok(())
}

```