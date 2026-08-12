---
title: "page_word_count"
second_title: "Aspose.PDF para Rust via C++"
description: "Retorna a contagem de palavras na página especificada no PDF-document."
type: docs
url: /pt/rust-cpp/core/page_word_count/
---

_Retorna a contagem de palavras na página especificada no PDF-document._

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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Especifique o número da página (índice baseado em 1)
    let page_number = 1;

    // Retorne a contagem de palavras na página especificada
    let count = pdf.page_word_count(page_number)?;

    // Imprima a contagem de palavras
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```