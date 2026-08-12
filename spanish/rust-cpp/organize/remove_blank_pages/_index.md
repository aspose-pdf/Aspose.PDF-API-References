---
title: "remove_blank_pages"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina páginas en blanco del documento PDF."
type: docs
url: /es/rust-cpp/organize/remove_blank_pages/
---

_Elimina páginas en blanco del documento PDF._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Eliminar páginas en blanco del documento PDF
    pdf.remove_blank_pages()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```