---
title: "rotate"
second_title: Aspose.PDF for Rust via C++
description: "Rotates the PDF-document."
type: docs
url: /rust-cpp/organize/rotate/
---

_Rotates the PDF-document._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** – rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Rotate PDF-document
    pdf.rotate(Rotation::On270)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```