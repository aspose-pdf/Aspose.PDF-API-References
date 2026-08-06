---
title: "add_text_header"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till text i rubriken på ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/add_text_header/
---

_Lägger till text i rubriken på ett PDF-dokument._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Lägg till text i rubriken på ett PDF-dokument
    pdf.add_text_header("HEADER")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```