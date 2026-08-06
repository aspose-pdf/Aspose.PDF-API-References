---
title: "validate"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanını PDF formatına uygunluk açısından doğrular."
type: docs
url: /tr/rust-cpp/organize/validate/
---

_PDF-dökümanını PDF formatına uygunluk açısından doğrular._

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
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Bir PDF-document'in PDF formatına uyumluluğunu doğrula
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Doğrulama sonucunu ve tam logu yazdır
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```