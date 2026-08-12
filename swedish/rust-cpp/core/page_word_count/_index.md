---
title: "page_word_count"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar antalet ord på den angivna sidan i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/page_word_count/
---

_Returnerar antalet ord på den angivna sidan i PDF-dokumentet._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Ange sidnumret (1-baserat index)
    let page_number = 1;

    // Returnera antalet ord på den angivna sidan
    let count = pdf.page_word_count(page_number)?;

    // Skriv ut antalet ord
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```