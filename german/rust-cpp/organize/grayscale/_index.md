---
title: "grayscale"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert das PDF-Dokument in Schwarzweiß."
type: docs
url: /de/rust-cpp/organize/grayscale/
---

_Konvertiert das PDF-Dokument in Schwarzweiß._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // Konvertiere PDF-Dokument in Schwarzweiß
    pdf.grayscale()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```