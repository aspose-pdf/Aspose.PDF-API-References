---
title: "split_at_page"
second_title: "Aspose.PDF für Rust über C++"
description: "Teilt das PDF-document in zwei neue PDF-documents."
type: docs
url: /de/rust-cpp/core/split_at_page/
---

_Teilt das PDF-document in zwei neue PDF-documents._

```rust
pub fn split_at_page(document: &Document, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
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

    // Teile das PDF-document in zwei neue PDF-documents
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // Speichere jeden geteilten Teil als separates PDF-document
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```