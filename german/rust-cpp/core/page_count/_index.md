---
title: "page_count"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt die Anzahl der Seiten im PDF-document zurück."
type: docs
url: /de/rust-cpp/core/page_count/
---

_Gibt die Anzahl der Seiten im PDF-document zurück._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Gib die Seitenanzahl im PDF-document zurück
    let count = pdf.page_count()?;

    // Gib die Seitenanzahl aus
    println!("Count: {}", count);

    Ok(())
}

```