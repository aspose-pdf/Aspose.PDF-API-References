---
title: "page_set_size"
second_title: "Aspose.PDF para Rust vía C++"
description: "Establece el tamaño de una página en el documento PDF."
type: docs
url: /es/rust-cpp/organize/page_set_size/
---

_Establece el tamaño de una página en el documento PDF._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Establecer el tamaño de una página en el documento PDF
    pdf.page_set_size(1, PageSize::A1)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```