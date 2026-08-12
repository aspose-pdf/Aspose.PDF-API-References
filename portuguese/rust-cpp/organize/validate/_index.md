---
title: "validate"
second_title: "Aspose.PDF para Rust via C++"
description: "Valida um documento PDF quanto à conformidade com o formato PDF."
type: docs
url: /pt/rust-cpp/organize/validate/
---

_Valida um documento PDF quanto à conformidade com o formato PDF._

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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Validar um documento PDF quanto à conformidade com o formato PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Imprimir resultado da validação e log completo
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```