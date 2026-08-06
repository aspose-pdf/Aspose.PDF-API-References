---
title: "save"
second_title: "Aspose.PDF för Rust via C++"
description: "Sparar det tidigare öppnade PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/save/
---

_Sparar det tidigare öppnade PDF-dokumentet._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med namnet "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Spara det tidigare öppnade PDF-dokumentet
    pdf.save()?;

    Ok(())
}

```