---
title: "optimize_file_size"
second_title: "Aspose.PDF para Rust vía C++"
description: "Optimiza el tamaño de un PDF-document con calidad de compresión de imagen."
type: docs
url: /es/rust-cpp/organize/optimize_file_size/
---

_Optimiza el tamaño de un PDF-document con calidad de compresión de imagen._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Optimizar el tamaño de un PDF-document con calidad de compresión de imagen
    pdf.optimize_file_size(50)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```