---
title: "remove_javascripts"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Java-Skripte aus dem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/remove_javascripts/
---

_Entfernt Java-Skripte aus dem PDF-Dokument._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // Entfernen Sie JavaScript aus dem PDF-Dokument
    pdf.remove_javascripts()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```