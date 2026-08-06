---
title: "set_background"
second_title: "Aspose.PDF för Rust via C++"
description: "Ställer in bakgrundsfärgen för PDF-dokument med RGB-värden."
type: docs
url: /sv/rust-cpp/organize/set_background/
---

_Ställer in bakgrundsfärgen för PDF-dokument med RGB-värden._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ställ in bakgrundsfärgen för PDF-dokument med RGB-värden
    pdf.set_background(200, 100, 101)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```