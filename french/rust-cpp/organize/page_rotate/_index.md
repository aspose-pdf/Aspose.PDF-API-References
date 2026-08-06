---
title: "page_rotate"
second_title: "Aspose.PDF pour Rust via C++"
description: "Fait pivoter une page du document PDF."
type: docs
url: /fr/rust-cpp/organize/page_rotate/
---

_Fait pivoter une page du document PDF._

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
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Faire pivoter la page
    pdf.page_rotate(1, Rotation::On180)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```