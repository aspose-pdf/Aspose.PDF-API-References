---
title: "beschneiden"
second_title: "Aspose.PDF für Rust über C++"
description: "Beschneidet Seiten eines PDF-Dokuments."
type: docs
url: /de/rust-cpp/organize/crop/
---

_Beschneidet Seiten eines PDF-Dokuments._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Seiten eines PDF-Dokuments beschneiden
    pdf.crop(10.5)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```