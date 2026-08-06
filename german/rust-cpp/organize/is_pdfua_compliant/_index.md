---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF für Rust über C++"
description: "Ermittelt, ob ein PDF-Dokument PDF/UA-konform ist."
type: docs
url: /de/rust-cpp/organize/is_pdfua_compliant/
---

_Ermittelt, ob ein PDF-Dokument PDF/UA-konform ist._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Erhalte den PDF/UA-Konformitätsstatus des PDF-Dokuments
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```