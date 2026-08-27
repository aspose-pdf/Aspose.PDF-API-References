---
title: "page_add_text"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt einer Seite Text hinzu."
type: docs
url: /de/rust-cpp/organize/page_add_text/
---

_Fügt einer Seite Text hinzu._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Text auf Seite hinzufügen
    pdf.page_add_text(1, "added text")?;

    // Speichere das zuvor geöffnete PDF-document
    pdf.save()?;

    Ok(())
}

```