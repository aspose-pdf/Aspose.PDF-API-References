---
title: "page_is_blank"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnera om sidan är tom i PDF-dokument."
type: docs
url: /sv/rust-cpp/core/page_is_blank/
---

_Sidan är tom i PDF-document._

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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Ange sidnumret (1-baserat index)
    let page_number = 1;

    // Sidan är tom i PDF-document
    let is_blank = pdf.page_is_blank(page_number)?;

    // Skriv ut om den angivna sidan är tom
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```