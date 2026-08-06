---
title: "page_add_text_header"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till text i sidhuvudet."
type: docs
url: /sv/rust-cpp/organize/page_add_text_header/
---

_Lägger till text i sidhuvudet._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Lägg till text i sidhuvud
    pdf.page_add_text_header(1, "HEADER")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```