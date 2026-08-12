---
title: "save_as"
second_title: "Aspose.PDF para Rust vía C++"
description: "Guarda el PDF-documento previamente abierto con un nuevo nombre de archivo."
type: docs
url: /es/rust-cpp/core/save_as/
---

_Guarda el PDF-documento previamente abierto con un nuevo nombre de archivo._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crear un nuevo PDF-documento
    let pdf = Document::new()?;

    // Guardar el PDF-documento con un nuevo nombre de archivo
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```