---
title: "page_delete"
second_title: "Aspose.PDF für Rust über C++"
description: "Löscht die angegebene Seite aus dem PDF-Dokument."
type: docs
url: /de/rust-cpp/core/page_delete/
---

_Löscht die angegebene Seite aus dem PDF-Dokument._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // Lösche die angegebene Seite im PDF-Dokument
    pdf.page_delete(1)?;

    // Speichere das zuvor geöffnete PDF-document
    pdf.save()?;

    Ok(())
}

```