---
title: "get_meta_info"
second_title: "Aspose.PDF para Rust vía C++"
description: "Obtiene el valor de la información meta del PDF-documento."
type: docs
url: /es/rust-cpp/core/get_meta_info/
---

_Obtiene el valor de la información meta del PDF-documento._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Obtener el valor de la información meta del PDF-documento
    let author = pdf.get_meta_info("Author")?;

    // Imprimir el resultado
    println!("Author: {}", author);

    Ok(())
}

```