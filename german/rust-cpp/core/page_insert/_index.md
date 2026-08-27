---
title: "page_insert"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt eine neue Seite an der angegebenen Position im PDF-document ein."
type: docs
url: /de/rust-cpp/core/page_insert/
---

_Fügt eine neue Seite an der angegebenen Position im PDF-document ein._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
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

    // Füge neue Seite an der angegebenen Position im PDF-document ein
    pdf.page_insert(1)?;

    // Speichere das zuvor geöffnete PDF-document
    pdf.save()?;

    Ok(())
}

```