---
title: "add_page_num"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega número de página a un PDF-document."
type: docs
url: /es/rust-cpp/organize/add_page_num/
---

_Agrega número de página a un PDF-document._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
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

    // Agregar número de página a un documento PDF
    pdf.add_page_num()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```