---
title: "page_count"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el número de páginas del PDF-document."
type: docs
url: /es/rust-cpp/core/page_count/
---

_Devuelve el número de páginas del PDF-document._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
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

    // Devolver el recuento de páginas en PDF-document
    let count = pdf.page_count()?;

    // Imprimir el recuento de páginas
    println!("Count: {}", count);

    Ok(())
}

```