---
title: "page_delete"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort den angivna sidan från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/page_delete/
---

_Tar bort den angivna sidan från PDF-dokumentet._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // Ta bort angiven sida i PDF-dokumentet
    pdf.page_delete(1)?;

    // Spara det tidigare öppnade PDF-dokumentet
    pdf.save()?;

    Ok(())
}

```