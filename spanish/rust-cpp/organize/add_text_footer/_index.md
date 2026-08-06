---
title: "add_text_footer"
second_title: "Aspose.PDF para Rust vía C++"
description: "Agrega texto en el pie de página de un PDF-document."
type: docs
url: /es/rust-cpp/organize/add_text_footer/
---

_Agrega texto en el pie de página de un PDF-document._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Agregar texto en el pie de página de un documento PDF
    pdf.add_text_footer("FOOTER")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```