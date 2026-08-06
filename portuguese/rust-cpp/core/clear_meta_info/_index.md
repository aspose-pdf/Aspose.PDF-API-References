---
title: "clear_meta_info"
second_title: "Aspose.PDF para Rust via C++"
description: "Limpa todos os valores de meta-informação do PDF-document."
type: docs
url: /pt/rust-cpp/core/clear_meta_info/
---

_Limpa todos os valores de meta-informação do PDF-document._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Limpar todos os valores de meta-informação do PDF-document
    pdf.clear_meta_info()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```