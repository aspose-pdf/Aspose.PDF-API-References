---
title: "page_add"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till en ny sida i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/page_add/
---

_Lägger till en ny sida i PDF-dokumentet._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Lägg till ny sida i PDF-dokument
    pdf.page_add()?;

    // Spara det tidigare öppnade PDF-dokumentet
    pdf.save()?;

    Ok(())
}

```