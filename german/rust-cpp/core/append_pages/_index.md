---
title: "append_pages"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt ausgewählte Seiten aus einem anderen PDF-document hinzu."
type: docs
url: /de/rust-cpp/core/append_pages/
---

_Fügt ausgewählte Seiten aus einem anderen PDF-document hinzu._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne das primäre PDF-document
    let pdf = Document::open("sample1page.pdf")?;

    // Ein weiteres PDF-Dokument zum Anhängen öffnen
    let another_pdf = Document::open("sample.pdf")?;

    // Füge bestimmte Seiten (1 und 3) aus einem anderen PDF-document hinzu
    pdf.append_pages(&another_pdf, "1,3")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```