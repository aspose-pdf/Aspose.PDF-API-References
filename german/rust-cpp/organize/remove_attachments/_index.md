---
title: "remove_attachments"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Anhänge aus PDF-document."
type: docs
url: /de/rust-cpp/organize/remove_attachments/
---

_Entfernt Anhänge aus PDF-document._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // Entfernen Sie Anhänge aus dem PDF-Dokument
    pdf.remove_attachments()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```