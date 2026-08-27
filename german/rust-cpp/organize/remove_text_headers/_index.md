---
title: "remove_text_headers"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Textköpfe aus PDF-document."
type: docs
url: /de/rust-cpp/organize/remove_text_headers/
---

_Entfernt Textköpfe aus PDF-document._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Textköpfe aus PDF-document entfernen
    pdf.remove_text_headers()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```