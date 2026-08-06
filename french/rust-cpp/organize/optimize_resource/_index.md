---
title: "optimiser_ressource"
second_title: "Aspose.PDF pour Rust via C++"
description: "Optimise les ressources du PDF-document."
type: docs
url: /fr/rust-cpp/organize/optimize_resource/
---

_Optimise les ressources du PDF-document._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // Optimiser les ressources du PDF-document
    pdf.optimize_resource()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```