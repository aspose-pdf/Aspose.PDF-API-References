---
title: "flatten"
second_title: Aspose.PDF for Rust via C++
description: "Flattens PDF-document."
type: docs
url: /rust-cpp/organize/flatten/
---

_Flattens PDF-document._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
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

    // Return the PDF-document contents as plain text
    let txt = pdf.extract_text()?;

    // Print extracted text
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```