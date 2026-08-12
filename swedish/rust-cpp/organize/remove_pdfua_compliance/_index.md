---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF för Rust via C++"
description: "Ta bort PDF/UA-kompatibilitet från ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/remove_pdfua_compliance/
---

_Ta bort PDF/UA-kompatibilitet från ett PDF-dokument._

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ta bort PDF/UA-efterlevnad från ett PDF-dokument
    pdf.remove_pdfua_compliance()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```