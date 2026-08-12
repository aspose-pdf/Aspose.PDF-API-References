---
title: "unembed_fonts"
second_title: "Aspose.PDF para Rust vía C++"
description: "Desincorpora fuentes de un PDF-document."
type: docs
url: /es/rust-cpp/organize/unembed_fonts/
---

_Desincorpora fuentes de un PDF-document._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Desincorporar fuentes de un PDF-document
    pdf.unembed_fonts()?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```