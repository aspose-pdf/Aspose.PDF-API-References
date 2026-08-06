---
title: "page_add_text_footer"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till text i sidfoten."
type: docs
url: /sv/rust-cpp/organize/page_add_text_footer/
---

_Lägger till text i sidfoten._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Lägg till text i sidfot
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```