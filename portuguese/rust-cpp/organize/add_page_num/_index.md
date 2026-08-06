---
title: "add_page_num"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona número de página a um PDF-document."
type: docs
url: /pt/rust-cpp/organize/add_page_num/
---

_Adiciona número de página a um PDF-document._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Adicionar número de página a um documento PDF
    pdf.add_page_num()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```