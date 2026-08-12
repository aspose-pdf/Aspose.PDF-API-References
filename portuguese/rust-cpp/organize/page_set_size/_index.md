---
title: "page_set_size"
second_title: "Aspose.PDF para Rust via C++"
description: "Define o tamanho de uma página no documento PDF."
type: docs
url: /pt/rust-cpp/organize/page_set_size/
---

_Define o tamanho de uma página no documento PDF._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Definir o tamanho de uma página no documento PDF
    pdf.page_set_size(1, PageSize::A1)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```