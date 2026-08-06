---
title: "remove_hidden_text"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt versteckten Text aus PDF-document."
type: docs
url: /de/rust-cpp/organize/remove_hidden_text/
---

_Entfernt versteckten Text aus PDF-document._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Entfernen Sie versteckten Text aus dem PDF-Dokument
    pdf.remove_hidden_text()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```