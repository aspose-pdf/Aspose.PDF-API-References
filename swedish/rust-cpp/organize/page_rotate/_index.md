---
title: "page_rotate"
second_title: "Aspose.PDF för Rust via C++"
description: "Roterar en sida i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/page_rotate/
---

_Roterar en sida i PDF-dokumentet._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Rotera sida
    pdf.page_rotate(1, Rotation::On180)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```