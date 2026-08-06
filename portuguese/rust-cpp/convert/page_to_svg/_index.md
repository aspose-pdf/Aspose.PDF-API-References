---
title: "page_to_svg"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva a página especificada como uma imagem SVG."
type: docs
url: /pt/rust-cpp/convert/page_to_svg/
---

_Converte e salva a página especificada como uma imagem SVG._

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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converter e salvar a página especificada como imagem SVG
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```