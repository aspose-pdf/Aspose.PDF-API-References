---
title: "split_at"
second_title: "Aspose.PDF für Rust über C++"
description: "Teilt das aktuelle PDF-Dokument in zwei neue PDF-Dokumente."
type: docs
url: /de/rust-cpp/core/split_at/
---

_Teilt das aktuelle PDF-Dokument in zwei neue PDF-Dokumente._

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
    // Öffne ein PDF-document mit dem Namen "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Teile das aktuelle PDF-Dokument in zwei neue PDF-Dokumente
    let (left, right) = pdf_split.split_at(2)?;

    // Speichere jeden geteilten Teil als separates PDF-document
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```