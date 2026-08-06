---
title: "add_text_header"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega texto en el encabezado de un PDF-document."
type: docs
url: /es/rust-cpp/organize/add_text_header/
---

_Agrega texto en el encabezado de un PDF-document._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Agregar texto en el encabezado de un documento PDF
    pdf.add_text_header("HEADER")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```