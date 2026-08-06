---
title: "page_is_blank"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devolver si la página está en blanco en el PDF-document."
type: docs
url: /es/rust-cpp/core/page_is_blank/
---

_La página devuelta está en blanco en el PDF-documento._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Especifica el número de página (índice basado en 1)
    let page_number = 1;

    // La página devuelta está en blanco en el PDF-documento
    let is_blank = pdf.page_is_blank(page_number)?;

    // Imprimir si la página especificada está en blanco
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```