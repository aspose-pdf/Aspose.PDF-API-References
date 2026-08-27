---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprime la conformité PDF/UA d'un document PDF."
type: docs
url: /fr/rust-cpp/organize/remove_pdfua_compliance/
---

_Supprime la conformité PDF/UA d'un document PDF._

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
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

    // Supprimer la conformité PDF/UA d'un PDF-document
    pdf.remove_pdfua_compliance()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```