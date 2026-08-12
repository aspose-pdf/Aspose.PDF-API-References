---
title: "recortar"
second_title: "Aspose.PDF para Rust vía C++"
description: "Recorta páginas de un documento PDF."
type: docs
url: /es/rust-cpp/organize/crop/
---

_Recorta páginas de un documento PDF._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Recortar páginas de un documento PDF
    pdf.crop(10.5)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```