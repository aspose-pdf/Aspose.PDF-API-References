---
title: "page_to_png"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva la pagina specificata come immagine PNG."
type: docs
url: /it/rust-cpp/convert/page_to_png/
---

_Converte e salva la pagina specificata come immagine PNG._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva la pagina specificata come immagine Png
    pdf.page_to_png(1, 100, "sample_page1.png")?;

    Ok(())
}

```