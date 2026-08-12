---
title: "page_remove_images"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina imágenes en la página."
type: docs
url: /es/rust-cpp/organize/page_remove_images/
---

_Elimina imágenes en la página._

```rust
pub fn page_remove_images(&self, num: i32) -> Result<(), PdfError>
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

    // Eliminar imágenes en la página
    pdf.page_remove_images(1)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_remove_images.pdf")?;

    Ok(())
}

```