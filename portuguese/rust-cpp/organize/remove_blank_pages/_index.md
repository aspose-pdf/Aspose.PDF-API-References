---
title: "remove_blank_pages"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove páginas em branco do PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_blank_pages/
---

_Remove páginas em branco do PDF-document._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Remover páginas em branco do documento PDF
    pdf.remove_blank_pages()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```