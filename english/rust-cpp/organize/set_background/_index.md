---
title: "set_background"
second_title: Aspose.PDF for Rust via C++
description: "Sets PDF-document background color using RGB values."
type: docs
url: /rust-cpp/organize/set_background/
---

_Sets PDF-document background color using RGB values._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** – red component (0-255)
  * **g** – green component (0-255)
  * **b** – blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Set PDF-document background color using RGB values
    pdf.set_background(200, 100, 101)?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```