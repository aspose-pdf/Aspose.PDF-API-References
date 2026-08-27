---
title: "validate"
second_title: "Aspose.PDF für Rust über C++"
description: "Validiert ein PDF-Dokument auf Konformität mit dem PDF-Format."
type: docs
url: /de/rust-cpp/organize/validate/
---

_Validiert ein PDF-Dokument auf Konformität mit dem PDF-Format._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Ein PDF-Dokument auf Konformität mit dem PDF-Format prüfen
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Validierungsergebnis und vollständiges Protokoll ausgeben
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```