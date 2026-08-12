---
title: "optimize"
second_title: "Aspose.PDF para Rust vía C++"
description: "Optimiza el contenido del documento PDF."
type: docs
url: /es/rust-cpp/organize/optimize/
---

_Optimiza el contenido del documento PDF._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Optimizar el contenido del documento PDF
    pdf.optimize()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```