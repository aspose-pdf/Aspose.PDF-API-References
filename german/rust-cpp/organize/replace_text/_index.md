---
title: "replace_text"
second_title: "Aspose.PDF für Rust über C++"
description: "Ersetzt Text."
type: docs
url: /de/rust-cpp/organize/replace_text/
---

_Ersetzt Text._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Ersetzen Sie Text im PDF-Dokument
    pdf.replace_text("PDF", "TXT")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```