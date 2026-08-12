---
title: "word_count"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el recuento de palabras en el PDF-documento."
type: docs
url: /es/rust-cpp/core/word_count/
---

_Devuelve el recuento de palabras en el PDF-documento._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // Devolver el recuento de palabras en el PDF-documento
    let count = pdf.word_count()?;

    // Imprimir el recuento de palabras
    println!("Word count: {}", count);

    Ok(())
}

```