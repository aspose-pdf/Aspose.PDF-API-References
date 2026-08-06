---
title: "page_is_blank"
second_title: "Aspose.PDF para Rust via C++"
description: "Retornar se a página está em branco no PDF-document."
type: docs
url: /pt/rust-cpp/core/page_is_blank/
---

_Retornar página está em branco no documento PDF._

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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Especifique o número da página (índice baseado em 1)
    let page_number = 1;

    // Retornar página está em branco no documento PDF
    let is_blank = pdf.page_is_blank(page_number)?;

    // Imprimir se a página especificada estiver em branco
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```