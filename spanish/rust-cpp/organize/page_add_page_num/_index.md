---
title: "page_add_page_num"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega número de página en la página."
type: docs
url: /es/rust-cpp/organize/page_add_page_num/
---

_Agrega número de página en la página._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Agregar número de página en la página
    pdf.page_add_page_num(1)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```