---
title: "set_background"
second_title: "Aspose.PDF para Rust vía C++"
description: "Establece el color de fondo del PDF-document usando valores RGB."
type: docs
url: /es/rust-cpp/organize/set_background/
---

_Establece el color de fondo del PDF-document usando valores RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Establecer el color de fondo del PDF-document usando valores RGB
    pdf.set_background(200, 100, 101)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```