---
title: "word_count"
second_title: "Aspose.PDF para Rust via C++"
description: "Retorna a contagem de palavras no PDF-document."
type: docs
url: /pt/rust-cpp/core/word_count/
---

_Retorna a contagem de palavras no PDF-document._

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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Retorne a contagem de palavras no PDF-document
    let count = pdf.word_count()?;

    // Imprima a contagem de palavras
    println!("Word count: {}", count);

    Ok(())
}

```