---
title: "new"
second_title: "Aspose.PDF para Rust vía C++"
description: "Crea un nuevo documento PDF."
type: docs
url: /es/rust-cpp/core/new/
---

_Crea un nuevo documento PDF._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crear un nuevo PDF-documento
    let pdf = Document::new()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```