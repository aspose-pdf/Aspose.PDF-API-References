---
title: "remove_hidden_text"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina texto oculto del documento PDF."
type: docs
url: /es/rust-cpp/organize/remove_hidden_text/
---

_Elimina texto oculto del documento PDF._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Eliminar texto oculto del documento PDF
    pdf.remove_hidden_text()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```