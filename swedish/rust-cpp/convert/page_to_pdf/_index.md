---
title: "page_to_pdf"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar den angivna sidan som ett PDF-dokument."
type: docs
url: /sv/rust-cpp/convert/page_to_pdf/
---

_Konverterar och sparar den angivna sidan som ett PDF-dokument._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara den angivna sidan som PDF-dokument
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```