---
title: "rotate"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ruota il PDF-document."
type: docs
url: /it/rust-cpp/organize/rotate/
---

_Ruota il PDF-document._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ruota PDF-document
    pdf.rotate(Rotation::On270)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```