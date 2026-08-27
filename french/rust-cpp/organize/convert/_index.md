---
title: "convertir"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit un PDF-document en un PDF-document avec le format PDF spécifié."
type: docs
url: /fr/rust-cpp/organize/convert/
---

_Convertit un PDF-document en un PDF-document avec le format PDF spécifié._

```rust
    pub fn convert(
        &self,
        pdf_format: PdfFormat,
        action: ConvertErrorAction,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))
  * **action** - the action to take on conversion errors (enum [ConvertErrorAction](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the conversion log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{ConvertErrorAction, Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Convertir un PDF-document en un PDF-document avec le format PDF spécifié
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Afficher le résultat de la conversion et le journal complet
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```