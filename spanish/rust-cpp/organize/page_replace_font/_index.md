---
title: "page_replace_font"
second_title: "Aspose.PDF para Rust vía C++"
description: "Reemplaza la fuente en la página."
type: docs
url: /es/rust-cpp/organize/page_replace_font/
---

_Reemplaza la fuente en la página._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Reemplazar fuente en la página
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```