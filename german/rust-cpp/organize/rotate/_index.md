---
title: "rotate"
second_title: "Aspose.PDF für Rust über C++"
description: "Dreht das PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/rotate/
---

_Dreht das PDF-Dokument._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // PDF-Dokument drehen
    pdf.rotate(Rotation::On270)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```