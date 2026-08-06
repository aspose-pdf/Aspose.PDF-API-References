---
title: "page_insert"
second_title: "Aspose.PDF para Rust via C++"
description: "Insere uma nova página na posição especificada no PDF-document."
type: docs
url: /pt/rust-cpp/core/page_insert/
---

_Insere uma nova página na posição especificada no PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Inserir nova página na posição especificada no PDF-document
    pdf.page_insert(1)?;

    // Salvar o PDF-document aberto anteriormente
    pdf.save()?;

    Ok(())
}

```