---
title: "page_crop"
second_title: "Aspose.PDF för Rust via C++"
description: "Beskär en sida."
type: docs
url: /sv/rust-cpp/organize/page_crop/
---

_Beskär en sida._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Beskär en sida
    pdf.page_crop(1, 1.0)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```