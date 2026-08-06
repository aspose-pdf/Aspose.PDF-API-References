---
title: "remove_bookmarks"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort bokmärken från PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/remove_bookmarks/
---

_Tar bort bokmärken från PDF-dokument._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
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

    // Ta bort bokmärken från PDF-dokument
    pdf.remove_bookmarks()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```