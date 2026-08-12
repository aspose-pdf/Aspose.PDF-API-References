---
title: "page_remove_text_footers"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort textfötter på sidan."
type: docs
url: /sv/rust-cpp/organize/page_remove_text_footers/
---

_Tar bort textfötter på sidan._

```rust
pub fn page_remove_text_footers(&self, num: i32) -> Result<(), PdfError>
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

    // Ta bort textfötter på sidan
    pdf.page_remove_text_footers(1)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_remove_text_footers.pdf")?;

    Ok(())
}

```