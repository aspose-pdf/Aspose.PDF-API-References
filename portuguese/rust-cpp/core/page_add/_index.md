---
title: "page_add"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona uma nova página ao documento PDF."
type: docs
url: /pt/rust-cpp/core/page_add/
---

_Adiciona uma nova página ao documento PDF._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Adicionar nova página no documento PDF
    pdf.page_add()?;

    // Salvar o PDF-document aberto anteriormente
    pdf.save()?;

    Ok(())
}

```