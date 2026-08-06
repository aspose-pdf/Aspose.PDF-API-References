---
title: "remove_watermarks"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort vattenstämplar från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_watermarks/
---

_Tar bort vattenstämplar från PDF-dokumentet._

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // Ta bort vattenstämplar från PDF-dokumentet
    pdf.remove_watermarks()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```