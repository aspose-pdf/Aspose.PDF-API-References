---
title: "save_docx_enhanced"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-document som ett DOCX-document med Enhanced Recognition Mode (fullt redigerbara tabeller och stycken)."
type: docs
url: /sv/rust-cpp/convert/save_docx_enhanced/
---

_Konverterar och sparar det tidigare öppnade PDF-document som ett DOCX-document med Enhanced Recognition Mode (fullt redigerbara tabeller och stycken)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara det tidigare öppnade PDF-document som DocX-document med Enhanced Recognition Mode (fullt redigerbara tabeller och stycken)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```