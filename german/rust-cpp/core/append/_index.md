---
title: "append"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt Seiten aus einem anderen PDF-document hinzu."
type: docs
url: /de/rust-cpp/core/append/
---

_Fügt Seiten aus einem anderen PDF-document hinzu._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne das primäre PDF-document
    let pdf = Document::open("sample.pdf")?;

    // Ein weiteres PDF-Dokument zum Anhängen öffnen
    let another_pdf = Document::open("sample1page.pdf")?;

    // Seiten aus einem anderen PDF-Dokument anhängen
    pdf.append(&another_pdf)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```