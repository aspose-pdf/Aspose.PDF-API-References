---
title: "page_grayscale"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert eine Seite in Schwarzweiß."
type: docs
url: /de/rust-cpp/organize/page_grayscale/
---

_Konvertiert eine Seite in Schwarzweiß._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Seite in Schwarzweiß konvertieren
    pdf.page_grayscale(1)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```