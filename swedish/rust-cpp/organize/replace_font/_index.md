---
title: "replace_font"
second_title: "Aspose.PDF för Rust via C++"
description: "Ersätter teckensnitt i ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/replace_font/
---

_Ersätter teckensnitt i ett PDF-dokument._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Byt ut typsnitt i ett PDF-dokument.
    pdf.replace_font("Helvetica", "Courier")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```