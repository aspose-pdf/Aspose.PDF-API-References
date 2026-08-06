---
title: "page_insert"
second_title: "Aspose.PDF para Rust vía C++"
description: "Inserta una nueva página en la posición especificada del PDF-documento."
type: docs
url: /es/rust-cpp/core/page_insert/
---

_Inserta una nueva página en la posición especificada del PDF-documento._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
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

    // Insertar nueva página en la posición especificada del PDF-documento
    pdf.page_insert(1)?;

    // Guardar el PDF-documento previamente abierto
    pdf.save()?;

    Ok(())
}

```