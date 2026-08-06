---
title: "embed_fonts"
second_title: "Aspose.PDF für Rust über C++"
description: "Bettet Schriftarten in ein PDF-Dokument ein."
type: docs
url: /de/rust-cpp/organize/embed_fonts/
---

_Bettet Schriftarten in ein PDF-Dokument ein._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // Schriftarten in ein PDF-Dokument einbetten
    pdf.embed_fonts()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```