---
title: "open"
second_title: "Aspose.PDF för Rust via C++"
description: "Öppnar ett PDF-document med filnamn."
type: docs
url: /sv/rust-cpp/core/open/
---

_Öppnar ett PDF-document med filnamn._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med namnet "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```