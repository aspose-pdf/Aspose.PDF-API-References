---
title: "page_add_text_header"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona texto no cabeçalho da página."
type: docs
url: /pt/rust-cpp/organize/page_add_text_header/
---

_Adiciona texto no cabeçalho da página._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Adicionar texto no cabeçalho da página
    pdf.page_add_text_header(1, "HEADER")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```