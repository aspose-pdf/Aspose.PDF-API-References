---
title: "ritaglia"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ritaglia le pagine di un documento PDF."
type: docs
url: /it/rust-cpp/organize/crop/
---

_Ritaglia le pagine di un documento PDF._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ritaglia le pagine di un documento PDF
    pdf.crop(10.5)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```