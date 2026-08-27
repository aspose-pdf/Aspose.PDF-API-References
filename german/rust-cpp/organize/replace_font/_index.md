---
title: "replace_font"
second_title: "Aspose.PDF für Rust über C++"
description: "Ersetzt die Schriftart in einem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/replace_font/
---

_Ersetzt die Schriftart in einem PDF-Dokument._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Schriftart in einem PDF-Dokument ersetzen.
    pdf.replace_font("Helvetica", "Courier")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```