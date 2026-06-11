---
title: "validate"
second_title: Aspose.PDF for Rust via C++
description: "Validates a PDF-document for compliance with the PDF format."
type: docs
url: /rust-cpp/organize/validate/
---

_Validates a PDF-document for compliance with the PDF format._

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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Validate a PDF-document for compliance with the PDF format
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Print validation result and full log
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```