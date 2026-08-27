---
title: "split"
second_title: "Aspose.PDF für Rust über C++"
description: "Erstellt mehrere neue PDF-documents, indem Seiten aus dem aktuellen PDF-document extrahiert werden."
type: docs
url: /de/rust-cpp/core/split/
---

_Erstellt mehrere neue PDF-documents, indem Seiten aus dem aktuellen PDF-document extrahiert werden._

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
    // Öffne ein PDF-document mit dem Namen "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Erstelle mehrere neue PDF-documents, indem Seiten aus dem aktuellen PDF-document extrahiert werden
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Speichere jeden geteilten Teil als separates PDF-document
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```