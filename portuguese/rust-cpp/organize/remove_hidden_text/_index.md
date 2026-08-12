---
title: "remove_hidden_text"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove texto oculto de PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_hidden_text/
---

_Remove texto oculto de PDF-document._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Remover texto oculto do documento PDF
    pdf.remove_hidden_text()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```