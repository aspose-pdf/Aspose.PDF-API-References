---
title: "convert"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte un documento PDF in un documento PDF con il formato PDF specificato."
type: docs
url: /it/rust-cpp/organize/convert/
---

_Converte un documento PDF in un documento PDF con il formato PDF specificato._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti un documento PDF in un documento PDF con il formato PDF specificato
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Stampa il risultato della conversione e il registro completo
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```