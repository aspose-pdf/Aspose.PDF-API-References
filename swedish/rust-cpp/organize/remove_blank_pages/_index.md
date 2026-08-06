---
title: "remove_blank_pages"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort tomma sidor från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_blank_pages/
---

_Tar bort tomma sidor från PDF-dokumentet._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
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

    // Ta bort tomma sidor från PDF-dokument
    pdf.remove_blank_pages()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```