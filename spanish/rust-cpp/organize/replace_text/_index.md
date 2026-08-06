---
title: "replace_text"
second_title: "Aspose.PDF para Rust vía C++"
description: "Reemplaza texto."
type: docs
url: /es/rust-cpp/organize/replace_text/
---

_Reemplaza texto._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Reemplazar texto en el documento PDF
    pdf.replace_text("PDF", "TXT")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```