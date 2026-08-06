---
title: "page_to_bmp"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda la página especificada como una imagen BMP."
type: docs
url: /es/rust-cpp/convert/page_to_bmp/
---

_Convierte y guarda la página especificada como una imagen BMP._

```rust
pub fn page_to_bmp(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **resolution_dpi** - the resolution in DPI
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

    // Convertir y guardar la página especificada como imagen Bmp
    pdf.page_to_bmp(1, 100, "sample_page1.bmp")?;

    Ok(())
}

```