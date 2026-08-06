---
title: "save_doc"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el documento PDF previamente abierto como un documento DOC."
type: docs
url: /es/rust-cpp/convert/save_doc/
---

_Convierte y guarda el documento PDF previamente abierto como un documento DOC._

```rust
pub fn save_doc(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir y guardar el documento PDF previamente abierto como documento Doc
    pdf.save_doc("sample.doc")?;

    Ok(())
}

```