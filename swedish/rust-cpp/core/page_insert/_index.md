---
title: "page_insert"
second_title: "Aspose.PDF för Rust via C++"
description: "Infogar en ny sida på den angivna positionen i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/page_insert/
---

_Infogar en ny sida på den angivna positionen i PDF-dokumentet._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Infoga ny sida på den angivna positionen i PDF-dokumentet
    pdf.page_insert(1)?;

    // Spara det tidigare öppnade PDF-dokumentet
    pdf.save()?;

    Ok(())
}

```