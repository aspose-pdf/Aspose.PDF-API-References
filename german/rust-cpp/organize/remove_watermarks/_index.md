---
title: "remove_watermarks"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Wasserzeichen aus PDF-document."
type: docs
url: /de/rust-cpp/organize/remove_watermarks/
---

_Entfernt Wasserzeichen aus PDF-document._

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // Wasserzeichen aus PDF-document entfernen
    pdf.remove_watermarks()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```