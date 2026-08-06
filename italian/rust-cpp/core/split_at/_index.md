---
title: "split_at"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Dividi il PDF-document corrente in due nuovi PDF-documents."
type: docs
url: /it/rust-cpp/core/split_at/
---

_Dividi il PDF-document corrente in due nuovi PDF-documents._

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
    // Apri un PDF-document chiamato "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Dividi il PDF-document corrente in due nuovi PDF-documents
    let (left, right) = pdf_split.split_at(2)?;

    // Salva ogni parte divisa come un PDF-document separato
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```