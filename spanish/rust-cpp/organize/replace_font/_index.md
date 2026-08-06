---
title: "replace_font"
second_title: "Aspose.PDF para Rust vía C++"
description: "Reemplaza la fuente en un documento PDF."
type: docs
url: /es/rust-cpp/organize/replace_font/
---

_Reemplaza la fuente en un documento PDF._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Reemplazar la fuente en un documento PDF.
    pdf.replace_font("Helvetica", "Courier")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```