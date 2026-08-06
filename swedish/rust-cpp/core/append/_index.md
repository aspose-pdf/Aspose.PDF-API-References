---
title: "append"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till sidor från ett annat PDF-dokument."
type: docs
url: /sv/rust-cpp/core/append/
---

_Lägger till sidor från ett annat PDF-dokument._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna det primära PDF-dokumentet
    let pdf = Document::open("sample.pdf")?;

    // Öppna ett annat PDF-document för att lägga till
    let another_pdf = Document::open("sample1page.pdf")?;

    // Lägg till sidor från ett annat PDF-document
    pdf.append(&another_pdf)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```