---
title: "remove_blank_pages"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt leere Seiten aus dem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/remove_blank_pages/
---

_Entfernt leere Seiten aus dem PDF-Dokument._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Entfernen Sie leere Seiten aus dem PDF-Dokument
    pdf.remove_blank_pages()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```