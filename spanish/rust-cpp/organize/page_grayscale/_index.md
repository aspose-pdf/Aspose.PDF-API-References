---
title: "page_grayscale"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte una página a blanco y negro."
type: docs
url: /es/rust-cpp/organize/page_grayscale/
---

_Convierte una página a blanco y negro._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Convertir página a blanco y negro
    pdf.page_grayscale(1)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```