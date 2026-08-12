---
title: "page_add_page_num"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till sidnummer på sidan."
type: docs
url: /sv/rust-cpp/organize/page_add_page_num/
---

_Lägger till sidnummer på sidan._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Lägg till sidnummer på sidan
    pdf.page_add_page_num(1)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```