---
title: "grayscale"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte el documento PDF a blanco y negro."
type: docs
url: /es/rust-cpp/organize/grayscale/
---

_Convierte el documento PDF a blanco y negro._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // Convertir documento PDF a blanco y negro
    pdf.grayscale()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```