---
title: "save_tiff"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o PDF-document aberto anteriormente como um documento Tiff."
type: docs
url: /pt/rust-cpp/convert/save_tiff/
---

_Converte e salva o PDF-document aberto anteriormente como um documento Tiff._

```rust
pub fn save_tiff(&self, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **resolution_dpi** - the resolution in DPI
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converta e salve o PDF-document aberto anteriormente como Tiff-document
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```