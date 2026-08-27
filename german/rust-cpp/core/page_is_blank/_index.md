---
title: "page_is_blank"
second_title: "Aspose.PDF für Rust über C++"
description: "Gib zurück, ob die Seite im PDF-Dokument leer ist."
type: docs
url: /de/rust-cpp/core/page_is_blank/
---

_Rückgabeseite ist im PDF-Dokument leer._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Geben Sie die Seitennummer an (1-basierter Index)
    let page_number = 1;

    // Rückgabeseite ist im PDF-Dokument leer
    let is_blank = pdf.page_is_blank(page_number)?;

    // Ausgeben, wenn die angegebene Seite leer ist
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```