---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF für Rust über C++"
description: "Ermittelt, ob ein PDF-Dokument PDF/A-konform ist."
type: docs
url: /de/rust-cpp/organize/is_pdfa_compliant/
---

_Ermittelt, ob ein PDF-Dokument PDF/A-konform ist._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
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

    // PDF/A-Konformitätsstatus des PDF-Dokuments abrufen
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```