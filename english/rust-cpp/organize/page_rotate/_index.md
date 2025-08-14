---
title: "page_rotate"
second_title: Aspose.PDF for Rust via C++
description: "Rotates a page in the PDF-document."
type: docs
url: /rust-cpp/organize/page_rotate/
---

_Rotates a page in the PDF-document._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Rotate page
    pdf.page_rotate(1, Rotation::On180)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```