---
title: "validate"
second_title: "Aspose.PDF för Rust via C++"
description: "Validerar ett PDF-dokument för överensstämmelse med PDF-formatet."
type: docs
url: /sv/rust-cpp/organize/validate/
---

_Validerar ett PDF-dokument för överensstämmelse med PDF-formatet._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Validera ett PDF-dokument för efterlevnad av PDF-formatet
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Skriv ut valideringsresultat och fullständig logg
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```