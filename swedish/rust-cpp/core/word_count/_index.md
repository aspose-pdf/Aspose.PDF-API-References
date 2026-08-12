---
title: "word_count"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar antalet ord i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/word_count/
---

_Returnerar antalet ord i PDF-dokumentet._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Returnera antalet ord i PDF-dokumentet
    let count = pdf.word_count()?;

    // Skriv ut antalet ord
    println!("Word count: {}", count);

    Ok(())
}

```