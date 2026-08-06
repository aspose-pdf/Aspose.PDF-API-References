---
title: "rotate"
second_title: "Aspose.PDF för Rust via C++"
description: "Roterar PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/rotate/
---

_Roterar PDF-dokumentet._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Rotera PDF-dokument
    pdf.rotate(Rotation::On270)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```