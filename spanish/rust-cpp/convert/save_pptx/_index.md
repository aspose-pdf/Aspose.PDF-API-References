---
title: "save_pptx"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el documento PDF previamente abierto como un documento PPTX."
type: docs
url: /es/rust-cpp/convert/save_pptx/
---

_Convierte y guarda el documento PDF previamente abierto como un documento PPTX._

```rust
pub fn save_pptx(&self, filename: &str) -> Result<(), PdfError>
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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Convertir y guardar el documento PDF previamente abierto como documento PptX
    pdf.save_pptx("sample.pptx")?;

    Ok(())
}

```