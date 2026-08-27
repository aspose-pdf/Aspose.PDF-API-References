---
title: "page_character_count"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt die Zeichenanzahl auf der angegebenen Seite im PDF-Dokument zurück."
type: docs
url: /de/rust-cpp/core/page_character_count/
---

_Gibt die Zeichenanzahl auf der angegebenen Seite im PDF-Dokument zurück._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Geben Sie die Seitennummer an (1-basierter Index)
    let page_number = 1;

    // Gib die Zeichenanzahl auf der angegebenen Seite zurück
    let count = pdf.page_character_count(page_number)?;

    // Zeichenanzahl ausgeben
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```