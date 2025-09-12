---
title: "page_remove_annotations"
second_title: Aspose.PDF for Rust via C++
description: "Removes annotations in page."
type: docs
url: /rust-cpp/organize/page_remove_annotations/
---

_Removes annotations in page._

```rust
pub fn page_remove_annotations(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Remove annotations in page
    pdf.page_remove_annotations(1)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_remove_annotations.pdf")?;

    Ok(())
}

```