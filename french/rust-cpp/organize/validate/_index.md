---
title: "validate"
second_title: "Aspose.PDF pour Rust via C++"
description: "Valide un PDF-document pour la conformité au format PDF."
type: docs
url: /fr/rust-cpp/organize/validate/
---

_Valide un PDF-document pour la conformité au format PDF._

```rust
    pub fn validate(
        &self,
        pdf_format: PdfFormat,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the validation log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Valider un PDF-document pour la conformité au format PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Imprimer le résultat de validation et le journal complet
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```