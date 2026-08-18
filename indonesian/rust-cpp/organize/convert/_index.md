---
title: "convert"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi PDF-document menjadi PDF-document dengan format PDF yang ditentukan."
type: docs
url: /id/rust-cpp/organize/convert/
---

_Mengonversi PDF-document menjadi PDF-document dengan format PDF yang ditentukan._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Konversi PDF-document menjadi PDF-document dengan format PDF yang ditentukan
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Cetak hasil konversi dan log lengkap
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```