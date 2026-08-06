---
title: "page_add_text"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona texto a uma página."
type: docs
url: /pt/rust-cpp/organize/page_add_text/
---

_Adiciona texto a uma página._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Adicionar texto na página
    pdf.page_add_text(1, "added text")?;

    // Salvar o PDF-document aberto anteriormente
    pdf.save()?;

    Ok(())
}

```