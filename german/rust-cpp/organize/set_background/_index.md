---
title: "set_background"
second_title: "Aspose.PDF für Rust über C++"
description: "Setzt die Hintergrundfarbe des PDF-Dokuments mithilfe von RGB-Werten."
type: docs
url: /de/rust-cpp/organize/set_background/
---

_Setzt die Hintergrundfarbe des PDF-Dokuments mithilfe von RGB-Werten._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Setze die Hintergrundfarbe des PDF-Dokuments mithilfe von RGB-Werten
    pdf.set_background(200, 100, 101)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```