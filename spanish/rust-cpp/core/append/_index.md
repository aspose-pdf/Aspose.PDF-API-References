---
title: "append"
second_title: "Aspose.PDF para Rust vía C++"
description: "Añade páginas de otro PDF-documento."
type: docs
url: /es/rust-cpp/core/append/
---

_Añade páginas de otro PDF-documento._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir el PDF-documento principal
    let pdf = Document::open("sample.pdf")?;

    // Abrir otro PDF-documento para añadir
    let another_pdf = Document::open("sample1page.pdf")?;

    // Añadir páginas de otro PDF-documento
    pdf.append(&another_pdf)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```