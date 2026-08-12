---
title: "page_replace_text"
second_title: "Aspose.PDF för Rust via C++"
description: "Ersätter text på sidan."
type: docs
url: /sv/rust-cpp/organize/page_replace_text/
---

_Ersätter text på sidan._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Byt ut text på sidan
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```