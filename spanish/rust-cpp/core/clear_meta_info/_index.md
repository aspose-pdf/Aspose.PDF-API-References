---
title: "clear_meta_info"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina todos los valores de información meta del PDF-document."
type: docs
url: /es/rust-cpp/core/clear_meta_info/
---

_Elimina todos los valores de información meta del PDF-document._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Eliminar toda la información meta del PDF-document
    pdf.clear_meta_info()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```