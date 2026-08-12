---
title: "remove_annotations"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove anotações do PDF-documento."
type: docs
url: /pt/rust-cpp/organize/remove_annotations/
---

_Remove anotações do PDF-documento._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Remover anotações do documento PDF
    pdf.remove_annotations()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```