---
title: "remove_images"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove imagens de PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_images/
---

_Remove imagens de PDF-document._

```rust
pub fn remove_images(&self) -> Result<(), PdfError>
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

    // Remover imagens do documento PDF
    pdf.remove_images()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_images.pdf")?;

    Ok(())
}

```