---
title: "est_pdfa_conforme"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtient si un PDF-document est conforme PDF/A."
type: docs
url: /fr/rust-cpp/organize/is_pdfa_compliant/
---

_Obtient si un PDF-document est conforme PDF/A._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Obtenir le statut de conformité PDF/A du PDF-document
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```