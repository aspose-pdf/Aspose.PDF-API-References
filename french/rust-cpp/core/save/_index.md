---
title: "save"
second_title: "Aspose.PDF pour Rust via C++"
description: "Enregistre le PDF-document précédemment ouvert."
type: docs
url: /fr/rust-cpp/core/save/
---

_Enregistre le PDF-document précédemment ouvert._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document nommé "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Enregistrer le PDF-document précédemment ouvert
    pdf.save()?;

    Ok(())
}

```