---
title: "page_word_count"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el recuento de palabras en la página especificada del PDF-documento."
type: docs
url: /es/rust-cpp/core/page_word_count/
---

_Devuelve el recuento de palabras en la página especificada del PDF-documento._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Especifica el número de página (índice basado en 1)
    let page_number = 1;

    // Devolver el recuento de palabras en la página especificada
    let count = pdf.page_word_count(page_number)?;

    // Imprimir el recuento de palabras
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```