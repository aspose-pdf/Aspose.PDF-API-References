---
title: "validate"
second_title: "Aspose.PDF para Rust vía C++"
description: "Valida un PDF-document para cumplir con el formato PDF."
type: docs
url: /es/rust-cpp/organize/validate/
---

_Valida un PDF-document para cumplir con el formato PDF._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Validar un documento PDF para el cumplimiento del formato PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Imprimir resultado de validación y registro completo
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```