---
title: "page_add_text_footer"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt Text in die Seitenfußzeile ein."
type: docs
url: /de/rust-cpp/organize/page_add_text_footer/
---

_Fügt Text in die Seitenfußzeile ein._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Text in der Seitenfußzeile hinzufügen
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```