---
title: "remove_text_headers"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina encabezados de texto del documento PDF."
type: docs
url: /es/rust-cpp/organize/remove_text_headers/
---

_Elimina encabezados de texto del documento PDF._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Eliminar encabezados de texto del documento PDF
    pdf.remove_text_headers()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```