---
title: "optimize"
second_title: "Aspose.PDF pour Rust via C++"
description: "Optimise le contenu du document PDF."
type: docs
url: /fr/rust-cpp/organize/optimize/
---

_Optimise le contenu du document PDF._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Optimiser le contenu du document PDF
    pdf.optimize()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```