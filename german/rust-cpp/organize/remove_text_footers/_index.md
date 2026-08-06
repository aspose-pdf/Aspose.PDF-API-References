---
title: "remove_text_footers"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Textfußzeilen aus dem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/remove_text_footers/
---

_Entfernt Textfußzeilen aus dem PDF-Dokument._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
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

    // Entferne Textfußzeilen aus dem PDF-Dokument
    pdf.remove_text_footers()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```