---
title: "page_character_count"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el recuento de caracteres en la página especificada del documento PDF."
type: docs
url: /es/rust-cpp/core/page_character_count/
---

_Devuelve el recuento de caracteres en la página especificada del documento PDF._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
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

    // Devolver el recuento de caracteres en la página especificada
    let count = pdf.page_character_count(page_number)?;

    // Imprimir el recuento de caracteres
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```