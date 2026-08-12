---
title: "remove_javascripts"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove scripts Java do documento PDF."
type: docs
url: /pt/rust-cpp/organize/remove_javascripts/
---

_Remove scripts Java do documento PDF._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // Remover scripts Java do documento PDF
    pdf.remove_javascripts()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```