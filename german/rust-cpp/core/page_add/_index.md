---
title: "page_add"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt dem PDF-Dokument eine neue Seite hinzu."
type: docs
url: /de/rust-cpp/core/page_add/
---

_Fügt dem PDF-Dokument eine neue Seite hinzu._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Neue Seite im PDF-Dokument hinzufügen
    pdf.page_add()?;

    // Speichere das zuvor geöffnete PDF-document
    pdf.save()?;

    Ok(())
}

```