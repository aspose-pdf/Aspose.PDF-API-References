---
title: "page_remove_watermarks"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort vattenstämplar på sidan."
type: docs
url: /sv/rust-cpp/organize/page_remove_watermarks/
---

_Tar bort vattenstämplar på sidan._

```rust
pub fn page_remove_watermarks(&self, num: i32) -> Result<(), PdfError>
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
    // Öppna ett PDF-dokument från fil
    let pdf = Document::open("sample.pdf")?;

    // Ta bort vattenstämplar på sidan
    pdf.page_remove_watermarks(1)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_remove_watermarks.pdf")?;

    Ok(())
}

```