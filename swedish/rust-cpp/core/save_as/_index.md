---
title: "save_as"
second_title: "Aspose.PDF för Rust via C++"
description: "Sparar det tidigare öppnade PDF-dokumentet med ett nytt filnamn."
type: docs
url: /sv/rust-cpp/core/save_as/
---

_Sparar det tidigare öppnade PDF-dokumentet med ett nytt filnamn._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Skapa ett nytt PDF-dokument
    let pdf = Document::new()?;

    // Spara PDF-dokumentet med ett nytt filnamn
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```