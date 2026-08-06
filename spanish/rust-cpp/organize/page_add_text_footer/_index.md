---
title: "page_add_text_footer"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega texto en el pie de página."
type: docs
url: /es/rust-cpp/organize/page_add_text_footer/
---

_Agrega texto en el pie de página._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Agregar texto en el pie de página de la página
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```