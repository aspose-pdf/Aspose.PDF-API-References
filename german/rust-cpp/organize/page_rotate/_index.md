---
title: "page_rotate"
second_title: "Aspose.PDF für Rust über C++"
description: "Dreht eine Seite im PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/page_rotate/
---

_Dreht eine Seite im PDF-Dokument._

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
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Seite drehen
    pdf.page_rotate(1, Rotation::On180)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```