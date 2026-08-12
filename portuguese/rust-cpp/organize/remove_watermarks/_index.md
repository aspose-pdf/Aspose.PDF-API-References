---
title: "remove_watermarks"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove marcas d'água de PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_watermarks/
---

_Remove marcas d'água de PDF-document._

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // Remove marcas d'água de PDF-document
    pdf.remove_watermarks()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```