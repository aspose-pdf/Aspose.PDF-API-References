---
title: "optimize_resource"
second_title: "Aspose.PDF för Rust via C++"
description: "Optimerar resurser i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/optimize_resource/
---

_Optimerar resurser i PDF-dokumentet._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Optimera resurser i PDF-dokument
    pdf.optimize_resource()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```