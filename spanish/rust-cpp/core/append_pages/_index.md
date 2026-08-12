---
title: "append_pages"
second_title: "Aspose.PDF para Rust vía C++"
description: "Añade páginas seleccionadas de otro PDF-document."
type: docs
url: /es/rust-cpp/core/append_pages/
---

_Añade páginas seleccionadas de otro PDF-document._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir el PDF-documento principal
    let pdf = Document::open("sample1page.pdf")?;

    // Abrir otro PDF-documento para añadir
    let another_pdf = Document::open("sample.pdf")?;

    // Añade páginas específicas (1 y 3) de otro PDF-document
    pdf.append_pages(&another_pdf, "1,3")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```