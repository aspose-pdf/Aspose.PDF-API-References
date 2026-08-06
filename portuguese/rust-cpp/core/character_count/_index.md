---
title: "character_count"
second_title: "Aspose.PDF para Rust via C++"
description: "Retorna a contagem de caracteres no documento PDF."
type: docs
url: /pt/rust-cpp/core/character_count/
---

_Retorna a contagem de caracteres no documento PDF._

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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Retornar a contagem de caracteres no documento PDF
    let count = pdf.character_count()?;

    // Imprimir a contagem de caracteres
    println!("Character count: {}", count);

    Ok(())
}

```