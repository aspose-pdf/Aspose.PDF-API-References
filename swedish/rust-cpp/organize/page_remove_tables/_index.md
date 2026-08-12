---
title: "page_remove_tables"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort tabeller på sidan."
type: docs
url: /sv/rust-cpp/organize/page_remove_tables/
---

_Tar bort tabeller på sidan._

```rust
pub fn page_remove_tables(&self, num: i32) -> Result<(), PdfError>
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

    // Ta bort tabeller på sidan
    pdf.page_remove_tables(1)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_page1_remove_tables.pdf")?;

    Ok(())
}

```