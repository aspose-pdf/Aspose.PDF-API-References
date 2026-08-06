---
title: "page_to_svg"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva la pagina specificata come immagine SVG."
type: docs
url: /it/rust-cpp/convert/page_to_svg/
---

_Converte e salva la pagina specificata come immagine SVG._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva la pagina specificata come immagine Svg
    pdf.page_to_svg(1, "sample_page1.svg")?;

    Ok(())
}

```