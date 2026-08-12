---
title: "page_rotate"
second_title: "Aspose.PDF para Rust vía C++"
description: "Rota una página en el documento PDF."
type: docs
url: /es/rust-cpp/organize/page_rotate/
---

_Rota una página en el documento PDF._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Rotar página
    pdf.page_rotate(1, Rotation::On180)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```