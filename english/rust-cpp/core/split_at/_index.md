---
title: "split_at"
second_title: Aspose.PDF for Rust via C++
description: "Splits the current PDF-document into two new PDF-documents."
type: docs
url: /rust-cpp/core/split_at/
---

_Splits the current PDF-document into two new PDF-documents._

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
    // Open a PDF-document named "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Split the current PDF-document into two new PDF-documents
    let (left, right) = pdf_split.split_at(2)?;

    // Save each split part as a separate PDF-document
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```