---
title: "bytes"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el contenido del documento PDF como un vector de bytes."
type: docs
url: /es/rust-cpp/core/bytes/
---

_Devuelve el contenido del documento PDF como un vector de bytes._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crear un nuevo PDF-documento
    let pdf = Document::new()?;

    // Devolver el contenido del documento PDF como un vector de bytes
    let data = pdf.bytes()?;

    // Imprimir la longitud del vector de bytes
    println!("Length: {}", data.len());

    Ok(())
}

```