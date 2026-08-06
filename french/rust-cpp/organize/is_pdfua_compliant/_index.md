---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtient si un document PDF est conforme PDF/UA."
type: docs
url: /fr/rust-cpp/organize/is_pdfua_compliant/
---

_Obtient si un document PDF est conforme PDF/UA._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // Obtenez le statut de conformité PDF/UA du document PDF
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```