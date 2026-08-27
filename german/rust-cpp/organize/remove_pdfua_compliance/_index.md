---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt die PDF/UA-Konformität von einem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/remove_pdfua_compliance/
---

_Entfernt die PDF/UA-Konformität von einem PDF-Dokument._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // PDF/UA-Konformität aus einem PDF-Dokument entfernen
    pdf.remove_pdfua_compliance()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```