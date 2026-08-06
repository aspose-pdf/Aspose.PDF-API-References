---
title: "remove_text_footers"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina pies de página de texto del documento PDF."
type: docs
url: /es/rust-cpp/organize/remove_text_footers/
---

_Elimina pies de página de texto del documento PDF._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // Eliminar pies de página de texto del documento PDF
    pdf.remove_text_footers()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```