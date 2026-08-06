---
title: "page_crop"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ritaglia una pagina."
type: docs
url: /it/rust-cpp/organize/page_crop/
---

_Ritaglia una pagina._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Ritaglia una pagina
    pdf.page_crop(1, 1.0)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```