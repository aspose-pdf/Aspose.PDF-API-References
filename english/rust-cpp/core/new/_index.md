---
title: "new"
second_title: Aspose.PDF for Rust via C++
description: "Creates a new PDF-document."
type: docs
url: /rust-cpp/core/new/
---

_Creates a new PDF-document._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Create a new PDF-document
    let pdf = Document::new()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```