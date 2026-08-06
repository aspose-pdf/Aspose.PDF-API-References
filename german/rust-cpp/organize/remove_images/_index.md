---
title: "remove_images"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Bilder aus PDF-document."
type: docs
url: /de/rust-cpp/organize/remove_images/
---

_Entfernt Bilder aus PDF-document._

```rust
pub fn remove_images(&self) -> Result<(), PdfError>
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

    // Entfernen Sie Bilder aus dem PDF-Dokument
    pdf.remove_images()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_images.pdf")?;

    Ok(())
}

```