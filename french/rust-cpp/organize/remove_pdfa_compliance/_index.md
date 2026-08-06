---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF pour Rust via C++"
description: "Supprimer la conformité PDF/A d'un PDF-document."
type: docs
url: /fr/rust-cpp/organize/remove_pdfa_compliance/
---

_Supprimer la conformité PDF/A d'un PDF-document._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Supprimer la conformité PDF/A d'un PDF-document
    pdf.remove_pdfa_compliance()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```