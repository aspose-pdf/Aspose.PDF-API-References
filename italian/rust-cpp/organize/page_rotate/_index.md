---
title: "page_rotate"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ruota una pagina nel documento PDF."
type: docs
url: /it/rust-cpp/organize/page_rotate/
---

_Ruota una pagina nel documento PDF._

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
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Ruota pagina
    pdf.page_rotate(1, Rotation::On180)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```