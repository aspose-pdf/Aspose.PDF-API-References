---
title: "clear_meta_info"
second_title: "Aspose.PDF für Rust über C++"
description: "Löscht alle Meta-Informationswerte des PDF-documents."
type: docs
url: /de/rust-cpp/core/clear_meta_info/
---

_Löscht alle Meta-Informationswerte des PDF-documents._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Lösche alle Meta-Informationswerte des PDF-documents
    pdf.clear_meta_info()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```