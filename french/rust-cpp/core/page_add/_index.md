---
title: "page_add"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute une nouvelle page au document PDF."
type: docs
url: /fr/rust-cpp/core/page_add/
---

_Ajoute une nouvelle page au document PDF._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Ajouter une nouvelle page dans le document PDF
    pdf.page_add()?;

    // Enregistrer le PDF-document précédemment ouvert
    pdf.save()?;

    Ok(())
}

```