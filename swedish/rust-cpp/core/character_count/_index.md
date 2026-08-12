---
title: "character_count"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar teckenantal i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/character_count/
---

_Returnerar teckenantal i PDF-dokumentet._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
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

    // Returnera teckenantal i PDF-dokumentet
    let count = pdf.character_count()?;

    // Skriv ut teckenantalet
    println!("Character count: {}", count);

    Ok(())
}

```