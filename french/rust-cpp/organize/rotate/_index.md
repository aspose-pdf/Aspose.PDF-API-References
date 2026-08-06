---
title: "rotate"
second_title: "Aspose.PDF pour Rust via C++"
description: "Fait pivoter le PDF-document."
type: docs
url: /fr/rust-cpp/organize/rotate/
---

_Fait pivoter le PDF-document._

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
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Faire pivoter le PDF-document
    pdf.rotate(Rotation::On270)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```