---
title: "convert"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar ett PDF-dokument till ett PDF-dokument med det angivna PDF-formatet."
type: docs
url: /sv/rust-cpp/organize/convert/
---

_Konverterar ett PDF-dokument till ett PDF-dokument med det angivna PDF-formatet._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera ett PDF-dokument till ett PDF-dokument med det angivna PDF-formatet
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Skriv ut konverteringsresultat och fullständig logg
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```