---
title: "page_set_size"
second_title: "Aspose.PDF för Rust via C++"
description: "Ställer in storleken på en sida i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/page_set_size/
---

_Ställer in storleken på en sida i PDF-dokumentet._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ställ in storleken på en sida i PDF-dokumentet
    pdf.page_set_size(1, PageSize::A1)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```