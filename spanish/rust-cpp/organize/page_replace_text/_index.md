---
title: "page_replace_text"
second_title: "Aspose.PDF para Rust vía C++"
description: "Reemplaza texto en la página."
type: docs
url: /es/rust-cpp/organize/page_replace_text/
---

_Reemplaza texto en la página._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Reemplazar texto en la página
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```