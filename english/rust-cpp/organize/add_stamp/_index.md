---
title: "add_stamp"
second_title: Aspose.PDF for Rust via C++
description: "Adds stamp to PDF-document."
type: docs
url: /rust-cpp/organize/add_stamp/
---

_Adds stamp to PDF-document._

```rust
pub fn add_stamp(
    &self,
    alternative_text: &str,
    image_data: &[u8],
    is_background: bool,
    x_indent: i32,
    y_indent: i32,
    height: i32,
    width: i32,
    rotation: Rotation,
    opacity: f64,
) -> Result<(), PdfError>
```

**Arguments**
  * **alternative_text** - the alternative stamp text
  * **image_data** - the raw bytes of the image
  * **is_background** - the stamp is background
  * **x_indent** - the x indent of the stamp
  * **y_indent** - the y indent of the stamp
  * **height** - the height of the stamp
  * **width** - the width of the stamp
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`
  * **opacity** - the opacity (decimal)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Load stamp image data
    let image_data = std::fs::read("stamp.png")?;

    // Add stamp to the PDF-document
    pdf.add_stamp(
        "Stamp",
        &image_data,
        true,
        100,
        100,
        50,
        50,
        Rotation::On180,
        0.5,
    )?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_add_stamp.pdf")?;

    Ok(())
}

```