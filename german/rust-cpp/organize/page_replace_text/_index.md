---
title: "page_replace_text"
second_title: "Aspose.PDF für Rust über C++"
description: "Ersetzt Text auf der Seite."
type: docs
url: /de/rust-cpp/organize/page_replace_text/
---

_Ersetzt Text auf der Seite._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Text auf der Seite ersetzen
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```