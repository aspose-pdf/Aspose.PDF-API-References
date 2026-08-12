---
title: "page_add_text_header"
second_title: "Aspose.PDF para Rust vía C++"
description: "Añade texto en el encabezado de la página."
type: docs
url: /es/rust-cpp/organize/page_add_text_header/
---

_Añade texto en el encabezado de la página._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Agregar texto en el encabezado de la página
    pdf.page_add_text_header(1, "HEADER")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```