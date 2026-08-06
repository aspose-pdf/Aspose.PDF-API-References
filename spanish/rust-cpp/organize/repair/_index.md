---
title: "repair"
second_title: "Aspose.PDF para Rust vía C++"
description: "Repara el documento PDF."
type: docs
url: /es/rust-cpp/organize/repair/
---

_Repara el documento PDF._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // Reparar documento PDF
    pdf.repair()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```