---
title: "split_at_page"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Divide il PDF-document in due nuovi PDF-documents."
type: docs
url: /it/rust-cpp/core/split_at_page/
---

_Divide il PDF-document in due nuovi PDF-documents._

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
    // Apri un PDF-document chiamato "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Dividi il PDF-document in due nuovi PDF-documents
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // Salva ogni parte divisa come un PDF-document separato
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```