---
title: "rotate"
second_title: "Aspose.PDF para Rust vía C++"
description: "Gira el documento PDF."
type: docs
url: /es/rust-cpp/organize/rotate/
---

_Gira el documento PDF._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Girar documento PDF
    pdf.rotate(Rotation::On270)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```