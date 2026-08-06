---
title: "save"
second_title: "Aspose.PDF para Rust vía C++"
description: "Guarda el PDF-documento previamente abierto."
type: docs
url: /es/rust-cpp/core/save/
---

_Guarda el PDF-documento previamente abierto._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento llamado "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Guardar el PDF-documento previamente abierto
    pdf.save()?;

    Ok(())
}

```