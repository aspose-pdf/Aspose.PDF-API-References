---
title: "page_add_text"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega texto a una página."
type: docs
url: /es/rust-cpp/organize/page_add_text/
---

_Agrega texto a una página._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Agregar texto en la página
    pdf.page_add_text(1, "added text")?;

    // Guardar el PDF-documento previamente abierto
    pdf.save()?;

    Ok(())
}

```