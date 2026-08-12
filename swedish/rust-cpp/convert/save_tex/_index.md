---
title: "save_tex"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-document som ett TeX-document."
type: docs
url: /sv/rust-cpp/convert/save_tex/
---

_Konverterar och sparar det tidigare öppnade PDF-document som ett TeX-document._

```rust
pub fn save_tex(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara det tidigare öppnade PDF-document som TeX-document
    pdf.save_tex("sample.tex")?;

    Ok(())
}

```