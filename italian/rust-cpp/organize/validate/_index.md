---
title: "validate"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Convalida un PDF-document per la conformità al formato PDF."
type: docs
url: /it/rust-cpp/organize/validate/
---

_Convalida un PDF-document per la conformità al formato PDF._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Convalida un documento PDF per la conformità al formato PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Stampa il risultato della convalida e il registro completo
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```