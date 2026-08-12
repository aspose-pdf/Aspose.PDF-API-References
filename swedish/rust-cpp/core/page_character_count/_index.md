---
title: "page_character_count"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar teckenantal på angiven sida i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/page_character_count/
---

_Returnerar teckenantal på angiven sida i PDF-dokumentet._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Ange sidnumret (1-baserat index)
    let page_number = 1;

    // Returnera teckenantal på den angivna sidan
    let count = pdf.page_character_count(page_number)?;

    // Skriv ut teckenantalet
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```