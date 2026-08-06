---
title: "page_add_page_num"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona número de página na página."
type: docs
url: /pt/rust-cpp/organize/page_add_page_num/
---

_Adiciona número de página na página._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Adicionar número da página na página
    pdf.page_add_page_num(1)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```