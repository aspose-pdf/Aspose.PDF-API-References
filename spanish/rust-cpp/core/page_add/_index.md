---
title: "page_add"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega una nueva página al documento PDF."
type: docs
url: /es/rust-cpp/core/page_add/
---

_Agrega una nueva página al documento PDF._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Agregar nueva página en el documento PDF
    pdf.page_add()?;

    // Guardar el PDF-documento previamente abierto
    pdf.save()?;

    Ok(())
}

```