---
title: "character_count"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el recuento de caracteres en el documento PDF."
type: docs
url: /es/rust-cpp/core/character_count/
---

_Devuelve el recuento de caracteres en el documento PDF._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Devolver el recuento de caracteres en el documento PDF
    let count = pdf.character_count()?;

    // Imprimir el recuento de caracteres
    println!("Character count: {}", count);

    Ok(())
}

```