---
title: "split"
second_title: "Aspose.PDF för Rust via C++"
description: "Skapar flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet."
type: docs
url: /sv/rust-cpp/core/split/
---

_Skapar flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med namnet "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Skapa flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Spara varje del som ett separat PDF-dokument
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```