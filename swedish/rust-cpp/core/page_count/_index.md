---
title: "page_count"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar antalet sidor i PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/page_count/
---

_Returnerar antalet sidor i PDF-dokumentet._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Returnera sidantal i PDF-dokument
    let count = pdf.page_count()?;

    // Skriv ut sidantalet
    println!("Count: {}", count);

    Ok(())
}

```