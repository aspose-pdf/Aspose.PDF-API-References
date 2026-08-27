---
title: "unembed_fonts"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt eingebettete Schriften aus einem PDF-document."
type: docs
url: /de/rust-cpp/organize/unembed_fonts/
---

_Entfernt eingebettete Schriften aus einem PDF-document._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Schriften aus einem PDF-document entfernen
    pdf.unembed_fonts()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```