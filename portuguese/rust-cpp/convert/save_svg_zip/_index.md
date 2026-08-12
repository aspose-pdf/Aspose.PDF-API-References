---
title: "save_svg_zip"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o PDF-documento previamente aberto como um SVG-archive."
type: docs
url: /pt/rust-cpp/convert/save_svg_zip/
---

_Converte e salva o PDF-documento previamente aberto como um SVG-archive._

```rust
pub fn save_svg_zip(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Converter e salvar o PDF-documento previamente aberto como SVG-archive
    pdf.save_svg_zip("sample_svg.zip")?;

    Ok(())
}

```