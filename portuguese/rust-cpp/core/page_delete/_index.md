---
title: "page_delete"
second_title: "Aspose.PDF para Rust via C++"
description: "Exclui a página especificada do PDF-document."
type: docs
url: /pt/rust-cpp/core/page_delete/
---

_Exclui a página especificada do PDF-document._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // Excluir página especificada no PDF-document
    pdf.page_delete(1)?;

    // Salvar o PDF-document aberto anteriormente
    pdf.save()?;

    Ok(())
}

```