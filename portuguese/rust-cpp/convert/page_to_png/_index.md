---
title: "page_to_png"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva a página especificada como imagem PNG."
type: docs
url: /pt/rust-cpp/convert/page_to_png/
---

_Converte e salva a página especificada como imagem PNG._

```rust
pub fn page_to_png(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converter e salvar a página especificada como imagem Png
    pdf.page_to_png(1, 100, "sample_page1.png")?;

    Ok(())
}

```