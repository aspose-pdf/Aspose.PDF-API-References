---
title: "split_at"
second_title: "Aspose.PDF för Rust via C++"
description: "Delar det aktuella PDF-dokumentet i två nya PDF-dokument."
type: docs
url: /sv/rust-cpp/core/split_at/
---

_Delar det aktuella PDF-dokumentet i två nya PDF-dokument._

```rust
pub fn split_at(&self, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **page** - a page number at which to split (1-based, exclusive for the second part)

**Returns**
  * **Ok((Self, Self))** - with the two split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med namnet "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Dela det aktuella PDF-dokumentet i två nya PDF-dokument
    let (left, right) = pdf_split.split_at(2)?;

    // Spara varje del som ett separat PDF-dokument
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```