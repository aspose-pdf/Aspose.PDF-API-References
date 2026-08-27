---
title: "remove_annotations"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Anmerkungen aus dem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/remove_annotations/
---

_Entfernt Anmerkungen aus dem PDF-Dokument._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Entfernen Sie Anmerkungen aus dem PDF-Dokument
    pdf.remove_annotations()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```