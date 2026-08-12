---
title: "set_meta_info"
second_title: "Aspose.PDF para Rust vía C++"
description: "Establece el valor de la información meta del PDF-document."
type: docs
url: /es/rust-cpp/core/set_meta_info/
---

_Establece el valor de la información meta del PDF-document._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Establecer el valor de la información meta del PDF-document
    pdf.set_meta_info("Author", "Aspose")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```