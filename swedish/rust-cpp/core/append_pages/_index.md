---
title: "append_pages"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till valda sidor från ett annat PDF-dokument."
type: docs
url: /sv/rust-cpp/core/append_pages/
---

_Lägger till valda sidor från ett annat PDF-dokument._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna det primära PDF-dokumentet
    let pdf = Document::open("sample1page.pdf")?;

    // Öppna ett annat PDF-document för att lägga till
    let another_pdf = Document::open("sample.pdf")?;

    // Lägg till specifika sidor (1 och 3) från ett annat PDF-dokument
    pdf.append_pages(&another_pdf, "1,3")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```