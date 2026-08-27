---
title: "save_docx_enhanced"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als DOCX-Dokument mit erweitertem Erkennungsmodus (vollständig editierbare Tabellen und Absätze)."
type: docs
url: /de/rust-cpp/convert/save_docx_enhanced/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als DOCX-Dokument mit erweitertem Erkennungsmodus (vollständig editierbare Tabellen und Absätze)._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als DOCX-Dokument mit erweitertem Erkennungsmodus (vollständig editierbare Tabellen und Absätze)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```