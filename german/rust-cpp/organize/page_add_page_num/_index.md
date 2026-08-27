---
title: "page_add_page_num"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt die Seitenzahl auf der Seite ein."
type: docs
url: /de/rust-cpp/organize/page_add_page_num/
---

_Fügt die Seitenzahl auf der Seite ein._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Seitennummer auf der Seite hinzufügen
    pdf.page_add_page_num(1)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```