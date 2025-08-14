---
title: "open"
second_title: Aspose.PDF for Rust via C++
description: "Opens a PDF-document with filename."
type: docs
url: /rust-cpp/core/open/
---

_Opens a PDF-document with filename._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document named "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```