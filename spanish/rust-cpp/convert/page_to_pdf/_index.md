---
title: "page_to_pdf"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda la página especificada como un PDF-document."
type: docs
url: /es/rust-cpp/convert/page_to_pdf/
---

_Convierte y guarda la página especificada como un PDF-document._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
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

    // Convertir y guardar la página especificada como PDF-document
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```