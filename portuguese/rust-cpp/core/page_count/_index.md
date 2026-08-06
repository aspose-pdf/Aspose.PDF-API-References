---
title: "page_count"
second_title: "Aspose.PDF para Rust via C++"
description: "Retorna o número de páginas no PDF-document."
type: docs
url: /pt/rust-cpp/core/page_count/
---

_Retorna o número de páginas no PDF-document._

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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Retornar contagem de páginas no PDF-document
    let count = pdf.page_count()?;

    // Imprimir a contagem de páginas
    println!("Count: {}", count);

    Ok(())
}

```