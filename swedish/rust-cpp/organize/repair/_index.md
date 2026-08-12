---
title: "repair"
second_title: "Aspose.PDF för Rust via C++"
description: "Reparerar PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/repair/
---

_Reparerar PDF-dokumentet._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // Reparera PDF-dokument
    pdf.repair()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```