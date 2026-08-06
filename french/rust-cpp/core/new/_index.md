---
title: "nouveau"
second_title: "Aspose.PDF pour Rust via C++"
description: "Crée un nouveau document PDF."
type: docs
url: /fr/rust-cpp/core/new/
---

_Crée un nouveau document PDF._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Créer un nouveau PDF-document
    let pdf = Document::new()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```