---
title: "add_text_header"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona texto no cabeçalho de um documento PDF."
type: docs
url: /pt/rust-cpp/organize/add_text_header/
---

_Adiciona texto no cabeçalho de um documento PDF._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Adicionar texto no cabeçalho de um documento PDF
    pdf.add_text_header("HEADER")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```