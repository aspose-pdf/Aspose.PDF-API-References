---
title: "page_remove_hidden_text"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove texto oculto na página."
type: docs
url: /pt/rust-cpp/organize/page_remove_hidden_text/
---

_Remove texto oculto na página._

```rust
pub fn page_remove_hidden_text(&self, num: i32) -> Result<(), PdfError>
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
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Remover texto oculto na página
    pdf.page_remove_hidden_text(1)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_remove_hidden_text.pdf")?;

    Ok(())
}

```