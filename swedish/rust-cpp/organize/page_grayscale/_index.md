---
title: "page_grayscale"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar en sida till svartvitt."
type: docs
url: /sv/rust-cpp/organize/page_grayscale/
---

_Konverterar en sida till svartvitt._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Konvertera sida till svartvitt
    pdf.page_grayscale(1)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```