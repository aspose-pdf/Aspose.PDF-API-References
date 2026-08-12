---
title: "page_to_svg"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda la página especificada como una imagen SVG."
type: docs
url: /es/rust-cpp/convert/page_to_svg/
---

_Convierte y guarda la página especificada como una imagen SVG._

```rust
pub fn page_to_svg(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Convertir y guardar la página especificada como imagen Svg
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```