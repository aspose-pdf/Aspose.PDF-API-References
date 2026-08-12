---
title: "add_page_num"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till sidnummer i ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/add_page_num/
---

_Lägger till sidnummer i ett PDF-dokument._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Lägg till sidnummer i ett PDF-dokument
    pdf.add_page_num()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```