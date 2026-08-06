---
title: "page_add_text"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till text på en sida."
type: docs
url: /sv/rust-cpp/organize/page_add_text/
---

_Lägger till text på en sida._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Lägg till text på sidan
    pdf.page_add_text(1, "added text")?;

    // Spara det tidigare öppnade PDF-dokumentet
    pdf.save()?;

    Ok(())
}

```