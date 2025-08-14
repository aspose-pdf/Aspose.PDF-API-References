---
title: "add_page_num"
second_title: Aspose.PDF for Rust via C++
description: "Adds page number to a PDF-document."
type: docs
url: /rust-cpp/organize/add_page_num/
---

_Adds page number to a PDF-document._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Add page number to a PDF-document
    pdf.add_page_num()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```