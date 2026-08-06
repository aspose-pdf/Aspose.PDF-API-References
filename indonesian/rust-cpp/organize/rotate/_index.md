---
title: "rotate"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Memutar dokumen PDF."
type: docs
url: /id/rust-cpp/organize/rotate/
---

_Memutar dokumen PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Putar dokumen PDF
    pdf.rotate(Rotation::On270)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```