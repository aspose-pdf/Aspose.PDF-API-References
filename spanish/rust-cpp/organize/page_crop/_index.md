---
title: "page_crop"
second_title: "Aspose.PDF para Rust vía C++"
description: "Recorta una página."
type: docs
url: /es/rust-cpp/organize/page_crop/
---

_Recorta una página._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Recortar una página
    pdf.page_crop(1, 1.0)?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```