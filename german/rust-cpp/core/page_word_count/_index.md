---
title: "page_word_count"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt die Wortanzahl auf der angegebenen Seite im PDF-Dokument zurück."
type: docs
url: /de/rust-cpp/core/page_word_count/
---

_Gibt die Wortanzahl auf der angegebenen Seite im PDF-Dokument zurück._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
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

    // Gib die Wortanzahl auf der angegebenen Seite zurück
    let count = pdf.page_word_count(page_number)?;

    // Gib die Wortanzahl aus
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```