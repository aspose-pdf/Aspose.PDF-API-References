---
title: "validate"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Memvalidasi dokumen PDF untuk kepatuhan terhadap format PDF."
type: docs
url: /id/rust-cpp/organize/validate/
---

_Memvalidasi dokumen PDF untuk kepatuhan terhadap format PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Validasi PDF-document untuk kepatuhan terhadap format PDF
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // Cetak hasil validasi dan log lengkap
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```