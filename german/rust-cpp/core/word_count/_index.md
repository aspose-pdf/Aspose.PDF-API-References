---
title: "word_count"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt die Wortanzahl im PDF-Dokument zurück."
type: docs
url: /de/rust-cpp/core/word_count/
---

_Gibt die Wortanzahl im PDF-Dokument zurück._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // Gib die Wortanzahl im PDF-Dokument zurück
    let count = pdf.word_count()?;

    // Gib die Wortanzahl aus
    println!("Word count: {}", count);

    Ok(())
}

```