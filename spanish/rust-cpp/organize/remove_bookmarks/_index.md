---
title: "remove_bookmarks"
second_title: "Aspose.PDF para Rust vía C++"
description: "Elimina marcadores del PDF-document."
type: docs
url: /es/rust-cpp/organize/remove_bookmarks/
---

_Elimina marcadores del PDF-document._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
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

    // Eliminar marcadores del documento PDF
    pdf.remove_bookmarks()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```