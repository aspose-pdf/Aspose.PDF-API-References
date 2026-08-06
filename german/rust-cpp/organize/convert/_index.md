---
title: "convert"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert ein PDF-document in ein PDF-document mit dem angegebenen PDF-Format."
type: docs
url: /de/rust-cpp/organize/convert/
---

_Konvertiert ein PDF-document in ein PDF-document mit dem angegebenen PDF-Format._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Ein PDF-Dokument in ein PDF-Dokument mit dem angegebenen PDF-Format konvertieren
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Konvertierungsergebnis und vollständiges Protokoll ausgeben
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```