---
title: "page_replace_font"
second_title: "Aspose.PDF för Rust via C++"
description: "Byter teckensnitt på sidan."
type: docs
url: /sv/rust-cpp/organize/page_replace_font/
---

_Byter teckensnitt på sidan._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Byt teckensnitt på sidan
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```