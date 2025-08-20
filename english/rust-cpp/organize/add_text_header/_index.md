---
title: "add_text_header"
second_title: Aspose.PDF for Rust via C++
description: "Adds text in Header of a PDF-document."
type: docs
url: /rust-cpp/organize/add_text_header/
---

_Adds text in Header of a PDF-document._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Add text in Header of a PDF-document
    pdf.add_text_header("HEADER")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```