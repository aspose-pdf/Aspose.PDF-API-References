---
title: "convert"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Belirtilen PDF formatı ile bir PDF-document'i başka bir PDF-document'e dönüştürür."
type: docs
url: /tr/rust-cpp/organize/convert/
---

_Belirtilen PDF formatı ile bir PDF-document'i başka bir PDF-document'e dönüştürür._

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
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Bir PDF-document'i belirtilen PDF formatıyla bir PDF-document'e dönüştür
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Dönüştürme sonucunu ve tam günlüğü yazdır
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```