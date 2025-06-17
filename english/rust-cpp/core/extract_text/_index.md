---
title: "extract_text"
second_title: Aspose.PDF for Rust via C++
description: "Returns the PDF-document contents as plain text."
type: docs
url: /rust-cpp/core/extract_text/
---

_Returns the PDF-document contents as plain text._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Return the PDF-document contents as plain text
    let txt = pdf.extract_text()?;

    // Print extracted text
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```