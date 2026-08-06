---
title: "page_crop"
second_title: "Aspose.PDF für Rust über C++"
description: "Beschneidet eine Seite."
type: docs
url: /de/rust-cpp/organize/page_crop/
---

_Beschneidet eine Seite._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Eine Seite beschneiden
    pdf.page_crop(1, 1.0)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```