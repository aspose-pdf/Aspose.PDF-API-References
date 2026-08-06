---
title: "repair"
second_title: "Aspose.PDF pour Rust via C++"
description: "Répare le document PDF."
type: docs
url: /fr/rust-cpp/organize/repair/
---

_Répare le PDF-document._

```rust
pub fn repair(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Réparer PDF-document
    pdf.repair()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```