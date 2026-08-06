---
title: "page_to_pdf"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva la pagina specificata come PDF-document."
type: docs
url: /it/rust-cpp/convert/page_to_pdf/
---

_Converte e salva la pagina specificata come PDF-document._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva la pagina specificata come PDF-document
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```