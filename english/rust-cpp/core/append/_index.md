---
title: "append"
second_title: Aspose.PDF for Rust via C++
description: "Appends pages from another PDF-document."
type: docs
url: /rust-cpp/core/append/
---

_Appends pages from another PDF-document._

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
    // Open the primary PDF-document
    let pdf = Document::open("sample.pdf")?;

    // Open another PDF-document to append
    let another_pdf = Document::open("sample1page.pdf")?;

    // Append pages from another PDF-document
    pdf.append(&another_pdf)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```