---
title: "page_add_text_header"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt Text in die Seitenkopfzeile ein."
type: docs
url: /de/rust-cpp/organize/page_add_text_header/
---

_Fügt Text in die Seitenkopfzeile ein._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Text in der Seitenkopfzeile hinzufügen
    pdf.page_add_text_header(1, "HEADER")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```