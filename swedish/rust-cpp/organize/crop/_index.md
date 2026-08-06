---
title: "beskär"
second_title: "Aspose.PDF för Rust via C++"
description: "Beskär sidor i ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/crop/
---

_Beskär sidor i ett PDF-dokument._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Beskär sidor i ett PDF-dokument
    pdf.crop(10.5)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```