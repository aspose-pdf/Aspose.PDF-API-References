---
title: "remove_text_headers"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove cabeçalhos de texto de PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_text_headers/
---

_Remove cabeçalhos de texto de PDF-document._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Remove cabeçalhos de texto de PDF-document
    pdf.remove_text_headers()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```